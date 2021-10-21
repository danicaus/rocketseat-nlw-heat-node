# DO WHILE 2021

Esse projeto foi desenvolvido durante a NLW Heat, realizada em Outubro de 2021. A trilha que desenvolveu essa aplicação foi a Impulse.

## **Objetivo da aplicação**

Essa aplicação é voltada para a troca de mensagens para comentar o evento da RocketSeat, que acontecerá no mês de Dezembro de 2021.

Os usuários deverão se logar no Github através do OAuth, e poderão criar novos comentários, bem como responder a comentários já criados.

## **Tecnologias utilizadas**

- Node.js
- TypeScript
- Prisma

## **Libs utilizadas**

- Axios
- Cors
- DotEnv
- Express
- jsonwebtoken
- socket.io

## **Desenvolvido em aula**


### **Aula 1 - Node**
*com Danielle Leão*

Logo na primeira aula desenvolvemos o backend da nossa aplicação.

Iniciamos preparando a autenticação do nosso usuário, permitindo que o usuário possa se autenticar no Github. Também criamos uma rota de callback para conseguirmos ter o retorno da api do Github, e aí avaliarmos se o usuário pode ter acesso ou não à nossa aplicação.

Em seguida criamos uma autenticação para nossa aplicação, a partir da configuração do Access token do Github. Capturamos os dados do usuário autenticado, e criamos o Prisma para trabalhar com o banco de dados. No Prisma, configuramos nossas migrations e tabelas (de messages e users), criando um banco de dados relacional.

Para a parte de mensagens, fizemos a comunicação com protocolo via websocket.

Outros serviços que incluímos foram o envio das últimas 3 mensagens publicadas e o retorno do perfil de usuário.

Essa aula já preparou o backend tanto para a aplicação em Desktop quando Mobile!

#

### **Aula 2 - React**
*com Diego Fernandes*

Pudemos desenvolver o frontend da plataforma, [de acordo com o Figma](https://www.figma.com/community/file/1031699316177416916) desenvolvido pelos designers da RocketSeat. O projeto ficou lindão!