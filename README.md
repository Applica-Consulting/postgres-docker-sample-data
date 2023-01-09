# PostgreSQL Docker setup with sample data
## Installation
- Install [Docker](https://docs.docker.com/get-docker/).
- Run docker / docker desktop
- Run `docker-compose up -d` in preferred terminal

## Use DataGrip
- Download [DataGrip](https://www.jetbrains.com/datagrip/download/#section=windows) and start a free trial.
- In the database explorer click "New" - "Data Source" - "PostgreSQL".
- Fill in username and password from `docker-compose.yml`
- In the field `Database:`, fill in `dellstore`.
- Click `OK`.
