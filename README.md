👋 Hii!!! Don't Forget to ⭐ repository 👨‍💻
# Docker-Container-Demo
How to containerise your Node JS application , Along with mongo and mongo-express container

CLONE [Docker-Container-Demo](https://github.com/joyal007/Docker-Container-Demo)

'**app**' directory contain Node JS application which is to be containerised.

Run below cmmd to build an image Node JS application
```
docker build -t my-app:1.0 .
```

'**container.yaml**' file contain docker-compose script to container of Node Js, mongo & mongo-express images.

```
docker-compose -f container.yaml up -d
```
