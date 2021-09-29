# Prova de Conceito - Strapi

Este projeto foi implementado com o objetivo de servir como material de estudo e primeiro contato com a ferramenta open-source Strapi.<br/>

Foi utilizada a documentação sobre [Strapi](https://strapi.io/documentation/developer-docs/latest/getting-started/introduction.html#open-source-contribution) como **material base para estudos**.

## 📌 Pré-requisitos

1. Yarn
2. Docker (Utilizado Docker Desktop)
3. Insomnia (opcional), para fazer as requisições.

## 📚 Instruções de uso

Como todo projeto em node, precisa-se: <br/>

1. Instalar as dependências existentes no package.json, com o comando `yarn`.<br/>
2. Rodar o banco pelo docker para que o projeto funcione corretamente, utilizando o comando `docker-compose up`.<br/>
3. Rodar em ambiente dev, com o comando `yarn develop`.
   <br/>

Após isso uma janela no navegador abrirá no endereço http://localhost:1337.

## 🧐 Observações importantes

1. Utilizou-se o banco de dados Postgres por meio do Docker, configurado pelo **docker-compose.yml**. Logo, será necessário ter na máquina para executá-lo da forma correta o Docker. Tendo isso em vista, basta rodar os comandos:

   - `docker-compose up` para ativar o banco
   - `docker-compose down` para desativá-lo.

2. No **1º acesso**, o Strapi pedirá para você **se registrar com um email e senha**. Essas credenciais serão utilizadas ao longo do desenvolvimento para que você consiga acessar a plataforma. Uma vez dentro, é possível configurar esses dados da forma como deseja.
