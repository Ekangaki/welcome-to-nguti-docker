https://raw.githubusercontent.com/Ekangaki/welcome-to-nguti-docker/main/Ekangaki-Suit-500x500.jpg

# Welcome to Docker

This is a repo for new users getting started with Docker.

You can try it out using the following command.
```
docker run -d -p 8088:80 --name welcome-to-nguti-docker ekangaki/nguti-docker:v1
```
And open `http://localhost:8088` in your browser.

# Building

Maintainers should see [MAINTAINERS.md](MAINTAINERS.md).

Build and run:
```
docker build -t welcome-to-nguti-docker . 
docker run -d -p 8088:3000 --name welcome-to-nguti-docker ekangaki/nguti-docker:v1
```
Open `http://localhost:8088` in your browser.
