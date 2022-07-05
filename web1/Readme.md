Essa é a pasta do Servidor Nginx

sudo docker build -t nginx:latest .

sudo docker run -ti --network rede_prova --ip 172.25.0.10 nginx:latest
