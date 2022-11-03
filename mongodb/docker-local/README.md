# Local MongoDB instance using Docker

In this page we will start a MongoDB instance inside of Docker

## Dependencies

Docker [Installation](../../docker/)

## Starting

Will be automatically removed after stopping

```sh
docker run --rm --name mongodb -p 27017:27017 -d mongo
```

Will keep the container after stopping

```sh
docker run --name mongodb -p 27017:27017 -d mongo
```

## Accessing `mongosh`

```sh
docker exec -it mongodb mongosh
```

## Killing

```sh
docker kill mongodb
```

## Removing (if started without `--rm` flag)

```sh
docker rm mongodb
```
