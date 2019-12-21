# Para rodar local

npm install
ng serve


## Development server

docker build -t angdock .
docker run -d -p 80:80 angdock
docker ps
docker exec nomeouidcontainer ls -la /usr/share/nginx/html/sgc/principal