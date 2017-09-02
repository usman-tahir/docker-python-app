# Docker with Python/Flask

### Prerequisites

Docker must be installed on your machine to use with this project. Please use
[this](https://www.docker.com/get-docker) link to determine what Docker product
best suits your needs.

### Running the application

In its current state, the application can be run by using the `docker-compose up`
command. This command uses the provided `docker-compose.yml` file to build and
run the application.

### Usage

Since the `docker-compose.yml` file specifies a bind mount through the use of
the `volumes` configuration option, any changes made to `app.py` can be seen
when the webpage running the application is loaded. Since this is a simple
application, this is the main feature that is exhibited thus far.