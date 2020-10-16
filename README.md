# App-Plex

## Running the Containers

1. Update the following mount points in [docker-compose.yml](./Docker/docker-compose.yml)
    * `../data/config:/config`
    * `../data/TV Shows:/tv`
    * `../data/Movies:/movies`
2. Run `docker-compose -f ./Docker/docker-compose.yml up -d`

## First Time Setup

1. Visit <http://your-ip:32400>
2. Log in
3. Configure Plex
