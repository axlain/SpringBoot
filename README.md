comandos
.\mvnw.cmd clean package 
docker build -t springboot-app .
docker run -it --rm -p 80:8080 springboot-app   
