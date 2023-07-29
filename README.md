# dolphinscheduler docker-compose running

## Command

* init database & schema

```code
docker-compose --profile schema  up -d
```

* Staring dolphinscheduler services

```code
docker-compose --profile all  up -d
```