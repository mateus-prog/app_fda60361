## Folder Structure

- #### laradock
- #### backend
## Installation Laradock
- #### Clone Laradock inside your PHP project:
```bash
      $ git clone https://github.com/mateus-prog/app_fda60361.git
```
- #### Enter the laradock folder and rename .env.example to .env.
```bash
    $ cp .env.example .env
```
- #### Run your containers:
```bash
    $ docker compose up -d nginx mariadb
```
- #### Enter the Workspace container, to execute commands like (Artisan, Composer, PHPUnit, Gulp, …)
```bash
    $ docker compose exec workspace bash
```    
## Configuration
 - #### Migrate

```bash
    $ php artisan migrate
```