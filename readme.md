 
 ### COMMANDS
 docker build -t myweb .
 docker image ls
 docker run -dit -p 8080:80 --name static-web myweb
 docker ps -a
 check IP or localhost:8080