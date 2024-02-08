# Aplicação CRUD com Node, Express & MongoDB

Este projeto é uma aplicação completa de CRUD (Create, Read, Update, Delete) construída com Node.js, Express e MongoDB.

## Pré-requisitos

Antes de começar, certifique-se de ter o Node.js e o MongoDB instalados em sua máquina.

## Configuração

1. Clone este repositório para a sua máquina local.
2. Navegue até a pasta do projeto.
3. Execute `npm install` para instalar todas as dependências.

## Configuração do Banco de Dados

Este projeto requer uma conexão com o MongoDB. Você precisará fornecer suas credenciais de conexão do MongoDB em um arquivo `config.env` na raiz do projeto.

O arquivo `config.env` deve ter o seguinte formato:


PORT=3000
MONGO_URI=mongodb+srv://admin:<password>@cluster0.utqdgve.mongodb.net/<username>?retryWrites=true&w=majority


Substitua `<password>` e `<username>` pelas suas credenciais do MongoDB.

## Executando o Projeto

Depois de concluir a configuração, você pode iniciar o servidor com `npm start`. O servidor será iniciado na porta especificada no arquivo `config.env`.