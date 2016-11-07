# omtd-docker

#required 
1. docker
2. docker-compose

#build
`docker-compose build`

#deploy
`docker-compose up` 
`docker-compose up -d` to run as daemon.

#remove
`docker-compose down` stops and deletes the containers.

#info
For development purposes this project assumes that the omtd-registry `Dockerfile` is located in `../omtd-registry`.
For production the latest war file from jenkins is going to be fetched.
