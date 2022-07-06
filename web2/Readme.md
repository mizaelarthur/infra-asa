Pasta para o servidor Apache

sudo docker build -t httpd:2.4 .

sudo docker run -ti --network rede_prova --ip 172.25.0.11 httpd:2.4
