👋 Hii!!! Don't Forget to ⭐ repository 👨‍💻
# Docker-Container-Demo
How to containerise your Node JS application , Along with mongo and mongo-express container

:octocat: CLONE [Docker-Container-Demo](https://github.com/joyal007/Docker-Container-Demo) Repository 📁

'**app**' directory contain Node JS application which is to be containerised.

Run below cmmd to build an image Node JS application
```
docker build -t my-app:1.0 .
```

'**container.yaml**' file contain docker-compose script to container of Node Js, mongo & mongo-express images.

```
docker-compose -f container.yaml up -d
```

You can ignore '**run.temp**' file it contain docker run script which helps in using mongo and mongo-express service during development phase.
