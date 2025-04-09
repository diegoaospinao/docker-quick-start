# .net core

## .net core build

```sh
dotnet build
```

## .net core run

```sh
dotnet run
```

# docker

## docker build

```sh
docker build -t weatherforecast-api .
```

## docker run

```sh
docker run -d -p 5000:8080 weatherforecast-api:latest
```

## docker publish to docker hub

```sh
docker login
docker tag weatherforecast-api:latest [your-dockerhub-username]/weatherforecast-api:latest
docker push [your-dockerhub-username]/weatherforecast-api:latest
```