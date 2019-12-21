# Para rodar local

npm install
ng serve


## Para rodar via docker

docker build -t angdock . </br>
docker run -d -p 80:80 angdock </br>

## Para verificar o conteudo dentro do nginx
docker ps </br>
docker exec nomeouidcontainer ls -la /usr/share/nginx/html/sgc/principal </br>
