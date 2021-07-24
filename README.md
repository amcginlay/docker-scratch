# docker-scratch

```bash
docker build -f Dockerfile.full -t hello-full .
docker build -f Dockerfile.scratch -t hello-scratch .

docker run hello-full
docker run hello-scratch

docker images
```

... compare the image sizes!
