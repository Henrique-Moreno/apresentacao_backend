Crie uma API REST simples utilizando apenas Node.js puro (módulo HTTP nativo), sem frameworks como Express e sem banco de dados.

### Requisitos

* Armazenar os dados dos pacientes em um array em memória.
* Cada paciente deve possuir:

  * id
  * nome
  * idade
  * convenio

### Rotas

**GET /pacientes**

* Retorna a lista completa de pacientes em formato JSON.

**GET /pacientes/:id**

* Retorna os dados de um paciente específico pelo ID.

### Tratamento de erros

* Caso o paciente não seja encontrado:

  * Retornar Status HTTP 404.
  * Retornar uma mensagem JSON informando que o paciente não foi encontrado.

* Caso a rota não exista:

  * Retornar Status HTTP 404.
  * Retornar uma mensagem JSON informando que a rota não existe.

### Requisitos técnicos

* Utilizar os códigos HTTP adequados.
* Configurar o cabeçalho Content-Type como application/json.
* Executar o servidor na porta 3000.
* Não utilizar bibliotecas externas.
* Comentar o código explicando as principais partes.

### Entrega

Ao final, explicar:

1. Como executar o projeto.
2. Como testar cada rota pelo navegador.
