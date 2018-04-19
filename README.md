# Laravel-dockerized-tutorial
Learning laravels basics inside docker containers

#### Command to install dependencies
```docker run --rm -v $(pwd):/app composer/composer install```

#### Folling command to fix permission problems
chmod -R o+w laravel_blog/storage

chmod -R o+w storage

sudo chmod 755 -R .