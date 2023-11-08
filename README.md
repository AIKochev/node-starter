## Node Starter Project

Build Docker Image:

```
docker build -t node-starter .
```

Create DockerHub repo and then tag and push image:

```
docker tag node-starter dockerHubAcc/node-starter
docker push dockerHubAcc/node-starter
```