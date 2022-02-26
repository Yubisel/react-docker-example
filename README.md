# React-Docker app example

## Development 

For development execute with docker-compose 

```
docker-compose up -d
```

## Production

Build the image and execute the command to go live with nginx server

```
$ docker build -t react-docker .
$ docker run -p 3000:80 react-docker
```

