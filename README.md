# Crevo-docker

Running development environments

## Usage

### Setup

```sh
$ docker-compose up --no-start
$ docker-compose run --rm elasticsearch elasticsearch-plugin install analysis-kuromoji
```

### Run

```sh
# Start command
$ docker-compose start [SERVICE]

# Stop command
$ docker-compose stop [SERVICE]
```

### Show log

```sh
$ docker-compose logs --follow [SERVICE]
```

### Show containers

```sh
$ docker-compose ps
```

### Cleanup

```sh
$ docker-compose down --volumes
```
