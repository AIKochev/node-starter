## Node Starter Project

Build Docker Image:

```
docker build -t node-starter .
```

Create DockerHub repo and then tag and push image:

```
docker tag node-starter docker-hub/node-starter
docker push docker-hub/node-starter
```

Run on a machine:

```
sudo docker run -d -rm -p 80:80 docker-hub/node-starter:tagname
```
