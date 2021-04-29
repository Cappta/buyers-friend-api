# Buyer's Friend API 💳

## Sobre
Essa é uma api JSON server responsável por prover os dados básicos de produtos, filiais e metódos de pagamento para o case técnico de front end do projeto buyer's friend.

## Como rodar a aplicação

### Passo 1:
Abra o terminal na pasta raiz do projeto e instale as dependencias através do npm.

NPM: `npm install`

### Passo 2:
Para subir a aplicação localmente, basta rodar o comando:

NPM: `npm start`

## Rotas e dados
### Para consultar a lista de produtos:

Método: GET

Rota: /products

Exemplo de retorno:

```
[
  {
      "id": "0001",
      "product_name": "COMPUTADOR RAZOR",
      "amount_in_cents": 500000
  },
  {
      "id": "0002",
      "product_name": "MONITOR SEM MARCA",
      "amount_in_cents": 20000
  }
]
```

### Para consultar a lista de filiais:

Método: GET

Rota: /subsidiary

Exemplo de retorno:

```
[
  {
    "id": 1, 
    "name": "PORTO ALEGRE"
  },
  {
    "id": 2, 
    "name": "SÃO PAULO"
  }
]
```

### Para consultar a lista de métodos de pagamento:

Método: GET

Rota: /paymentMethod

Exemplo de retorno:

```
[
  {
    "id": 1, 
    "name": "PAGAMENTO PARCELADO"
  },
  {
    "id": 2,
    "name": "PAGAMENTO À VISTA"
  }
]
```
