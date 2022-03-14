# Estudo de API com Node
## Comandos Iniciais

1. Cria a pasta do projeto
2. Abrir a pasta no terminal
3. npm init -y
4. npm install express nodemon
5. Cria o script de start
6. npm start

## Os Endpoints

1. GET
  * http://localhost:3000/

Recebe a mensagem: Status 200
{
    "message": "Primeira rota criada com sucesso!"
}

2. POST
  * http://localhost:3000/createproduct

Colocado o produto no Body:
{
    "name": "Cadeira",
    "price": 29.99
}

Recebe a mensagem: Status 201
{
    "message": "O produto Cadeira foi criado com sucesso!"
}

## Status de ERRO

Faltando o nome do produto, o status é 422, com a mensagem:
{
    "message": "O campo nome é obrigatório!"
}
