# OUTPUT Wordpress Docker 

Docker setup for local development

## Setup
1. Install docker and docker-compose
2. Create a backup of the Wordpress Site with the Duplicator Plugin
2. Put the `installer.php` and `xxxx_archive.zip` file into `/src`
3. Run `docker-compose up -d`
4. Open browser and type `localhost:4000/installer.php`
5. Follow further instructions from Duplicator
6. Give your host user write access to the `/src` folder