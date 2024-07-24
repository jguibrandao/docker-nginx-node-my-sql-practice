# desafio-docker-nginx-node-mysql

Desafio do curso FullCycle, no módulo de Docker.

# Desafio:

- Através de um proxy reverso, o usuário deve acessar nossa aplicação NodeJS e inserir um item em nossa tabela MySQL.

# Funcionamento:

```html
<h1>Full Cycle Rocks!</h1>

- A aplicação, a cada requisição no nosso nginx, ativa o nosso arquivo node,
insere um nome aleatório através da biblioteca "faker" e nos mostra estes itens
em "localhost:8080".
```

# Pré requisitos

1. A aplicação deve estar na porta 8080.

### Para rodar :rocket:

```
git clone https://github.com/jguibrandao/docker-nginx-node-my-sql-practice.git

cd docker-nginx-node-my-sql-practice

docker-compose up [-d]
```

<br/>
<br/>
