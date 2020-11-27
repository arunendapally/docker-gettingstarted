# Steps to follow

- docker images
- docker build -t arunendapally/my-nginx:demo .
- docker images
- docker run -d --name myapp -p 8080:80 arunendapally/my-nginx:demo
- http://localhost:8080/
- docker ps
- docker stop [container id]
- docker rm [container id]
- docker rmi [image id]
