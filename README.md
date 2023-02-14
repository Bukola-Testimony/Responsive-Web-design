 docker build -t myweb .
 docker run -dit -p 8080:80 --name static-web myweb
 check IP or localhost:8080