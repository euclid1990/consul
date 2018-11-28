# Consul
Discovering and configuring services with Consul and Registrator

## Run

```
$ docker volume create consul_data
$ docker run --rm --entrypoint htpasswd registry:2 -Bbn testuser testpassword > .htpasswd
$ docker-compose up
```

## UI

`http://localhost:8500/ui/dc1/services`
