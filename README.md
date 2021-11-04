# PG Admin Docker Container

## About This Repository

This is designed to function as a template to be shared with individuals who want to easily install PG Admin via docker on their local desktops.

## Getting Started

### Deployment

Please make sure to have docker installed (simplest way is to install [Docker Desktop](https://www.docker.com/products/docker-desktop))!

Update the variable: `${PATH-TO-LOCAL-VOLUME}` in the file `docker-compose.yml` with the path you would like to use to house your volume data.

Navigate to the directory via command line where you cloned this repository and run:
```
docker-compose up -d --build --remove-orphans
```
This should start the service on localhost:5556.

## Help

Always appreciated.

## Authors

Contributors names and contact info

    Alexander Bogdanowicz[@akbog]
