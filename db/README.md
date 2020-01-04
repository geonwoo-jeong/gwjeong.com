# DB

## Create Docker Networks

```
sudo docker network create --driver bridge --subnet 10.10.10.0/24 --gateway 10.10.10.1 database
sudo docker network create --driver bridge --subnet 10.10.20.0/24 --gateway 10.10.20.1 pgadmin

```

## Create .ENV

```
POSTGRES_USER
POSTGRES_PASSWORD
PGADMIN_DEFAULT_EMAIL
PGADMIN_DEFAULT_PASSWORD
```

```
sudo docker-compose up -d
```
