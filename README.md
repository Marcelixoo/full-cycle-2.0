# full-cycle-2.0

Este repositório contêm o código-fonte dos desafios propostos durante o curso Full Cycle 2.0.

## Docker
-----

O primeiro módulo apresenta dois desafios.

1. Uma simples aplicação Golang para printar uma determinada mensagem quando rodada em um  container
2. Uma aplicação Node.js que se comunica com o banco de dados para ler um nome cadastrado no momento de build. Está aplicação é disponibilizada através de um proxy reverso implementado pelo Ngninx.

### Aplicação Golang
Está aplicação deverá mostrar na tela a mensagem "Code.education Rocks!" quando executada. A aplicação está disponível através de uma imagem Docker armazenada no Docker Hub. Para executá-la, basta rodar o comando a seguir:

```bash
    docker run --rm marcelixoo/codeeducation
```

O código-fonte da aplicação está disponível em [docker/desafio-go](docker/desafio-go/app.go).
