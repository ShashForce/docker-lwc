# docker-lwc

Here will be some information about the app.

## How to start?

[`Make sure you have Docker setup`](https://www.docker.com/get-started)

Start simple by `cd`ing into the repo and running 
either `docker build -t dockerlwc .` and then `docker run -p 3001:3001 dockerlwc`,
or just `docker-compose up` 
This will start a local docker container
Access localhost:3000

The source files are located in the [`src`](./src) folder. All web components are within the [`src/modules`](./src/modules) folder. The folder hierarchy also represents the naming structure of the web components.
