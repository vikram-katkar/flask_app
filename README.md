# flask_app
Hello World Flask App

Usage

```sh
# Build docker image
docker build -t flask .

# Run docker image
docker run -d -p 8080:8080 --name hello-world-flask flask

# Access the app
curl localhost:8080
```

```sh
# Stop container and remove
docker rm hello-world-flask -f
```

