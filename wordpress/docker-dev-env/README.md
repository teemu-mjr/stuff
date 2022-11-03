# WordPress development environment

In this page we are going to set up a development environment for WordPress using Docker.

## Dependencies

Docker [Installation](../../docker/)

## Starting a new WordPress project with `docker compose`

1. Create a new folder for the project

   ```sh
   mkdir wordpress-project
   ```

2. Copy the given `docker-compose.yml` file to the new folder

3. Start the docker containers

   ```sh
   docker compose up -d
   ```

4. Open the local WordPress site

   [http://localhost:8080](http://localhost:8080)
