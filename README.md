# easy-redmine

## How to use

### Start the containers.
```sh
docker compose up -d
```
or
```sh
./up.sh
```

### Stop the containers.
```sh
dockerk compose down
```
or
```sh
./down.sh
```

### delete datas
If you delete all datas, execute these commands.  
```sh
docker volume rm redmine_postgres_data
docker volume rm redmine_redmine_data
docker volume rm redmine_redmine_plugins
```
