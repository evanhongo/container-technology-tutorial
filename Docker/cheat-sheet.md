```
docker build -t <image_name> .
docker images
docker run -d -p 3000:8080 --name <container_name> <image_name>
docker ps -a
docker logs <containerID>
docker stop <containerID>
docker start <containerID>
docker exec -it <containerID> bash
```
