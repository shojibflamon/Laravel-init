# laravel-init
This repository will make env, migration, seeding, installation, vhost, setup without hassle

## Step 1 [Laravel initialization before installation]
- cd var/www/html
- git clone https://example.com/username/repo.git
- cd repo
- cp webserver/nginx/laravel-boilerplate.local.example webserver/nginx/blog.local
- cp Makefile.example Makefile

## Step 2 [Modifying]
- update repo.local as your requirements
- update Makefile as your requirements

## Step 3 [Install Laravel]
- composer create-project laravel/laravel blog
- mv blog/* .
- rmdir blog

## Step 4 [Setup]
- make setup