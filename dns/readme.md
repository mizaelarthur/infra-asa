Essa é a Pasta do Servidor DNS

Para Execução do mesmo, crie uma nova network no seu docker com o seguinte comando:

docker network create -d bridge --subnet 172.25.0.0/24 rede_prova

docker build -t ubuntu/bind9:latest .

sudo docker run -ti --network rede_prova ubuntu/bind9:latest
