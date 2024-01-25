# laravel-init
This repository will make env, migration, seeding, installation, vhost, setup without hassle

## Step 1 [Laravel initialization before installation]
- cd var/www/html
- git clone https://github.com/shojibflamon/laravel-init.git blog
- cd blog
- cp webserver/nginx/laravel-boilerplate.local.example webserver/nginx/blog.local
- cp Makefile.example Makefile

## Step 2 [Modifying]
- update repo.local as your requirements
- update Makefile as your requirements

## Step 3 [Install Laravel for fresh installation]
- composer create-project laravel/laravel blog
- sudo rm -rd .git
- mv -f blog/{.,}* .
- rmdir blog

## Step 4 [Clone Existing Laravel Project]
- git clone https://example.com/username/blog.git
- sudo rm -rd .git
- mv -f blog/{.,}* .
- rmdir blog

## Step 4 [Setup]
- make setup