# Symfony Franken MySQL API Template

## Getting started

```sh
docker compose build --pull --no-cache
docker compose up -d
docker compose exec php composer install
docker compose exec php bin/console doctrine:migrations:migrate
docker compose exec php bin/console doctrine:fixtures:load
```
