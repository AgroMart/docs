# Arquitetura do Agromart

![diagrama_arquitetura](https://github.com/user-attachments/assets/20ec5a5d-3c09-48c0-b294-fa1ea33d6d21)

O Agromart é composto por três componentes principais: o aplicativo móvel, a API Dicionário e a API principal de cada CSA, como mostra a figura acima. O funcionamento da aplicação consiste em uma API principal, administrada por cada CSA, que registra a URL do seu servidor na API Dicionário, que através do aplicativo móvel, possibilita o consumidor se conectar a uma das CSAs listadas na API Dicionário e interagir diretamente com ela.

O aplicativo móvel tem o objetivo de ser usado pelos clientes para realizar pedidos nas lojas da CSA escolhida. As tecnologias utilizadas no aplicativo móvel são: TypeScript, que é uma versão tipada da linguagem de programação JavaScript; React Native, um framework para desenvolvimento mobile multiplataforma; e Expo, uma plataforma que simplifica o desenvolvimento de aplicativos usando React Native. Atualmente, o aplicativo está disponível apenas na versão Android, mas, por ter sido desenvolvido utilizando o React Native, que é uma ferramenta multi plataforma, é possível, futuramente, com poucas adaptações, disponibilizar uma versão iOS do aplicativo.

A API principal da CSA, tem o objetivo de salvar os dados dos produtos, planos, clientes e lojas de uma CSA. Cada CSA deve ter seu próprio servidor, desse modo, o Agromart é uma aplicação que funciona de forma decentralizada, sem qualquer interação entre os servidores de cada CSA. A API da CSA é feita na linguagem JavaScript, utilizando a ferramenta Strapi como Sistema Gerenciador de Conteúdo.
Além de ser consumida pelo aplicativo, a API principal também disponibiliza um painel de administração da CSA, onde é possível cadastrar produtos, visualizar pedidos entre outras funcionalidades.

A API Dicionário tem o objetivo de registrar as URLs de cada uma das CSAs que utilizam o Agromart, para que ao utilizar o App do Agroamrt, o usuário possa através dos endereços cadastrados na API Dicionário se conectar o servidor da CSA Desejada. A API Dicionário foi desenvolvida a linguagem JavaScript e o PostgreSQL como Sistema Gerenciador de Banco de Dados.

Anteriormente, existia um repositório web para os administradores das CSAs, mas, em trabalhos anteriores, esse painel foi arquivado, pois o painel de administrador disponibilizado pelo Strapi acessível através da API principal era uma forma mais eficiente de utilizar as funcionalidades de administrador da CSA.


# Uso do gh pages
This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.
### Installation
```
$ yarn
```
### Local Development
```
$ yarn start
```
This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.
### Build
```
$ yarn build
```
This command generates static content into the `build` directory and can be served using any static contents hosting service.
### Deployment
```
$ GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```
If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
