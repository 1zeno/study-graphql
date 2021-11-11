#### Estudo de GraphQL

### Motivação para usar graphql:

Retorna apenas os dados que o front precisa de acordo com a necessidade dele ao invés de retornar
todas as colunas de uma determinada tabela, assim, evitando o overfetching. Dessa forma, reduz
o custo da aplicação devido a menor quantidade de tráfego de dados; 

## Exemplos de response:

````
Rest:

[ 
    {"name": "Agobaldo Nunes", "email": "agobaldonunes292@gmail.com", "idade": 30}
    {"name": "Bigail Bil", "email": "bigabil03@gmail.com", "idade": 43}
]


GraphQL:

[ 
    {"name": "Agobaldo Nunes"}
    {"name": "Bigail Bil"}
]
````

### Requisições:

Diferente do REST, todas as requisições são POST e sempre são direcionadaspara o mesmo endpoint.

## Query:

São utilizadas para obter informações (semelhante ao método GET do REST).

## Mutation:

São utilizadas para manipular dados (semelhante aos métodos  POST/PUT/PATCH/DELETE do REST).

## Scalar Types:

São os tipos primitivos, sendo eles: Int, Float, String, Boolean, e ID.
(Haverá um tópico apenas para scalar types adiante)
