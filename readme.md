## Feng Huang Institute Docker Compose Project

This Project contains the Docker Feng Huang Institute`s Compose files  that
orchestrate all the site ecosystem.

This project can be used for development and production workflow.

For production, I use a private `docker-compose.yml` override file, 
with diferent configurations like restart policy (e.g., `restart: always`) to 
avoid services downtile.


See `docker-compose.yml` and `docker-compose.override.yml` files 
for more details.

### TODO

- Explain how to start project with docker