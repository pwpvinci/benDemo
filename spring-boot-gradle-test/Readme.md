docker build -t sbhui/bentest -f src/main/docker/Dockerfile .

$ docker run -p 8002:8080 sbhui/bentest