# Escolha da Imagem para servidor DNS
FROM ubuntu/bind9

# Checkagem para atualizações do sistema e instalção do DNSUTILS
RUN apt update
RUN apt upgrade -y
RUN apt install dnsutils -y

# Copiando todos os arquivos que estão dentro de "etc" para dentro do Container
COPY ./etc/* /etc/bind



