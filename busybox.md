# To run busybox

## Go to `hello-front`
```
cd hello-front
```

## Start container
```
docker compose up
```

## In a new terminal, run busybox
```
docker compose run debug-helper wget -O - http://app:3000
```
## See FullStackOpen [here](https://fullstackopen.com/en/part12/basics_of_orchestration#communication-between-containers-in-a-docker-network) for more detail