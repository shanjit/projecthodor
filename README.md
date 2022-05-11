## Docker 

docker build -t sapratyaya . --build-arg giturl=https://github.com/shanjit/projecthodor.git
docker run -p <port>:80 -d -t sapratyaya
