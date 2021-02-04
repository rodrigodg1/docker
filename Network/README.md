# Networking

criar um ambiente de comunicação entre containers

em cada nó:
> docker run -it ubuntu

pode-se verificar o endereço ip utilizando:

> hostname -i

para enviar um ping (ICMP) é necessário instalar o pacote iputils-ping

> apt-get update && apt-get install -y iputils-ping
