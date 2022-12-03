# EduBlock Deployment

> NOTE: edit config.yml in server-data before using

## Start services

```sh
docker-compose up --detach
```

## Stop services

```sh
docker-compose down
```

## Cleanup

```sh
docker-compose down --volumes --rmi
```

## Guide

- Step 1: Start services then stop it
- Step 2: Update server config file
- Step 3: Start services again with updated configurations