# full-stack-CRUD
# t r a b a l h o p 1 b a n c o 
 


# Projeto Full-Stack CRUD
# Projeto Full-Stack CRUD - MizaelMarques - Banco de Dados

## O que é isso?

Esse é um projeto de aplicação full-stack CRUD, ou seja, uma aplicação que faz as operações básicas de banco de dados: Criar, Ler, Atualizar e Excluir (CRUD). O frontend é feito com React e Vite, enquanto o backend ainda precisa ser detalhado. A ideia é ter uma interface interativa no frontend e um backend funcional para suportar as operações.

## Como está organizado o projeto?

O projeto está organizado da seguinte forma:

- **frontend/**: Aqui fica todo o código do lado do cliente (frontend).
- **package.json**: Contém as dependências e scripts do frontend.
- **backend/**: Está usando `uvicorn` e `pymysql` para se conectar ao banco de dados (ainda não detalhado).

## Frontend

A parte do frontend foi construída com React e configurada pelo Vite, o que deixa o desenvolvimento bem rápido. Aqui estão as principais dependências:

### Dependências Principais

- axios: ^1.8.4
- react: ^19.0.0
- react-dom: ^19.0.0
- react-router-dom: ^7.5.0

### Scripts que você pode rodar

- **dev**: Rodar o servidor de desenvolvimento com o Vite.
- **build**: Criar a versão de produção da aplicação.
- **lint**: Executa o ESLint para ver se o código tem algum erro ou precisa de ajustes.
- **preview**: Abre o servidor de preview para visualizar como a versão de produção vai ficar.

### Configuração do ESLint

No projeto, o ESLint está configurado para ajudar a garantir que o código esteja bem escrito e sem erros. Ele tem algumas regras para o React também.

### Dica para Produção

Se for colocar isso em produção, seria legal usar TypeScript e configurar o ESLint de uma forma que garanta um código mais seguro e sem problemas com tipos.

## Backend

(Os detalhes do backend não estão aqui ainda. Vou adicionar quando tiver mais informações sobre ele.)

## Como rodar no seu computador

### Desenvolvimento Local

1. Vá para a pasta do frontend e instale as dependências com:  
   `cd frontend`  
   `npm install`
2. Para rodar o servidor de desenvolvimento, é só usar:  
   `npm run dev`

### Criando a versão de Produção

Para gerar a versão final, você pode rodar:  
`npm run build`

### Visualizando a Build

Depois de rodar o build, você pode conferir a versão de produção com:  
`npm run preview`

## Contribuindo

Se quiser ajudar a melhorar, pode abrir um pull request ou criar uma issue para sugerir melhorias ou relatar algum problema.

## Licença

Esse projeto está licenciado pela MIT License.

