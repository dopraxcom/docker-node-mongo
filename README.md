# Add MONGODB_HOST environment variable  to main
Look up the host name of the mongodb instance that  is created in your services tab and enter it as environment variable with key of MONGODB_HOST
# Docker Node MongoDB Example

> Simple example of a dockerized Node/Mongo app

![Image](https://i.ibb.co/4Fgt31L/demo.gif)

## Quick Start

```bash
# Run in Docker
docker-compose up
# use -d flag to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build
```
