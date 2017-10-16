# INFRA ESTRUTURA COMO CDIGO

Para executar tenha instalado o docker e o docker-compose

# Instalando docker e docker-compose

# Docker:
Comando para instalar:

wget -qO- https://get.docker.com/ | sh

Comando para testar:

docker container run hello-world

Verificar versão instalada:

docker --version

# Docker-compose

Comando de instalação:

sudo curl -L https://github.com/docker/compose/releases/download/1.16.1/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose

Configurar como executável:

sudo chmod +x /usr/local/bin/docker-compose

Verificar versão instalada:

docker-compose --version

# Rodando a estrutura como código

Clone o repositorio e execute o comando:

docker-compose up

# URLs:

phpmyadmin: http://localhost:8080
Composer: http://localhost:8000
