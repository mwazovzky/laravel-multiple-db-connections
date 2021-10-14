# Multiple database migrations

## Configure multiple database connection

See 'config/database.php'

## Create separate `migrations` table for database connection [optional]

`php artisan migrate:install --database=archive`

## Run migrations for specifoed database connection

`php artisan migrate --database="archive" --path=database/migrations/archive`
