# CustomerHive_Hosting

## Installazione


```bash
docker-compose up -d
```
```bash
docker-compose exec app php artisan migrate --force
```

```bash
docker-compose exec app php artisan db:seed
```
## Aggiornamento

```bash
docker compose down
```
```bash
docker compose pull
```

```bash
docker compose up -d
```
```bash
docker-compose exec app php artisan migrate --force
```

```bash
docker-compose exec app php artisan db:seed
```
