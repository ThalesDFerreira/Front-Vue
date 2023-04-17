Projeto Frent-End com VUE

Descrição

O Projeto Frent-End com VUE é uma aplicação web direcionada para pedidos em restaurantes, sendo que no exemplo fora feito para realizar pedidos de diferentes Burgers.

Tecnologias utilizadas

Node.js Vue HTML CSS

Instalação

Clone o repositório (sem as aspas):
https ==> "git clone https://github.com/ThalesDFerreira/Front-Vue.git" ou SSH ==> "git clone git@github.com:ThalesDFerreira/Front-Vue.git"

Entre no diretório clonado:
"cd Front-Vue"

Tendo em vista que você já tenha o Docker instalado em sua máquina, execute o seguinte comando para subir a aplicação (container):
"docker-compose up -d"

Após o processo finalizar, certifique-se que ocorreu tudo bem:
"docker ps -a" OBS: verifique se existe os containers rodando ex: front-vue-backend-1 e front-vue-frontend-1"

Se ocorreu tudo bem, basta acessar do seu navegador de internet a porta "3000":
"localhost:3000"

Após realizar as devidas avaliações e visualizações digite o comando no seu terminal para baixar a aplicação docker (container):
"docker-compose down"