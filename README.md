# Simple Postgresql template for database course


## First time installation

```
./first-time-install.sh
```


## Run Postgresql container

```
./run.sh
```

## Stop Postgresql container

```
./stop.sh
```

## Run bash session in container

```
./run-bash-session.sh
```

## Clean database

```
sudo rm -rf data
```

## Scripts within container

You can find the SQL scripts you write in the `scripts` dir in `/opt/postgresql/scripts` inside the container.
