# Desafio Técnico/Teórico QA

**Prazo do desafio**: Informado no recebimento do e-mail.

## Desafio Técnico/Teórico

### TDD/BDD

Este desafio visa avaliar a compreensão de duas abordagens ágeis amplamente utilizadas no desenvolvimento de software: TDD (Test-Driven Development) e BDD (Behavior-Driven Development). Embora TDD e BDD sejam abordagens usadas somente por DESENVOLVEDORES, este exercício tem como objetivo também ajudar a instruir o time de desenvolvimento a começar a escrever testes unitários de maneira eficiente.

O candidato deve responder às perguntas abaixo e, em seguida, implementar os testes unitários utilizando TDD/BDD com base no que foi solicitado.

#### TDD

##### Perguntas

1. Quais são as duas regras principais do TDD?
2. Com base nas duas regras do TDD, qual é a ordem correta para a execução das tarefas durante o ciclo de desenvolvimento no TDD?
3. Quais são as três leis do TDD?

##### Código

O Product Owner solicitou a implementação de uma nova regra no sistema para validar se uma pessoa é menor de idade ou não, a fim de determinar se ela pode consumir bebida alcoólica.

Com isso, foram definidos os seguintes requisitos funcionais:

- RF001: Pessoas maiores de 17 anos podem consumir bebida alcoólica.
- RF002: Pessoas menores de 17 anos não podem consumir bebida alcoólica.

###### Como entregar o desafio

- Criar um repositório no GitHub com o nome `qa.tdd-mocha.javascript`
- Criar a classe `Pessoa` em javascript que contenha o método `ehMaiorDeIdade(idade)` que será testado.
- Desenvolver somente os testes unitários necessários para esses dois requisitos usando o [Mocha JS](https://mochajs.org/)
- Explicar qual técnica de teste e porque foi utilizada para levantar os casos de testes? (colocar no arquivo readme.md)
- Enviar o link do repositório público via e-mail.
- O arquivo readme.md do projeto deve conter as respostas das 3 perguntas, deve explicar quais configurações são necessárias para executar o projeto, além de como instalar e executar o projeto manualmente.

###### Itens que Serão Avaliados

- Código limpo e organizado
- Correta entrega do que foi solicitado
- Organização do código, testes e demais arquivos.
- Pipeline configurada no GitHub Actions executando os testes unitários.
- O arquivo readme.md bem documentado

#### BDD

##### Perguntas

1. Com base no vídeo [BDD não é automação de teste](https://www.youtube.com/watch?v=O_FiotmX0R4) de uma das grandes referências da nossa área de qualidade 'Elias Nogueira', explique com suas palavras o que é o BDD e como aplica-ló da maneira correta no ciclo de desenvolvimento de software?

##### Código

O Product Owner solicitou a implementação de uma nova regra no sistema para validar se uma pessoa é menor de idade ou não, a fim de determinar se ela pode consumir bebida alcoólica.

Com isso, foram definidos os seguintes requisitos funcionais (comportamentos):

- RF001: Pessoas maiores de 17 anos podem consumir bebida alcoólica.
- RF002: Pessoas menores de 17 anos não podem consumir bebida alcoólica.

###### Como entregar o desafio

- Criar um repositório no GitHub com o nome `qa.bdd-cucumberjs.javascript`
- Criar a classe `Pessoa` em javascript que contenha o método `ehMaiorDeIdade(idade)` que será testado.
- Criar um arquivo `pessoa.feature` com os comportamentos descritos em gherkin declarativo dos cenários a serem automatizados
- Usando a biblioteca do [cucumber.js](https://cucumber.io/docs/installation/javascript/), crie todos os testes unitários necessários para esses dois requisitos (comportamentos)
- Enviar o link do repositório público via e-mail.
- O arquivo readme.md do projeto deve conter a resposta da pergunta, deve explicar quais configurações são necessárias para executar o projeto, além de como instalar e executar o projeto manualmente.

###### Itens que Serão Avaliados

- Código limpo e organizado
- Correta entrega do que foi solicitado
- Organização do código, testes e demais arquivos.
- Pipeline configurada no GitHub Actions executando os testes unitários.
- O arquivo readme.md bem documentado

### WEB

> **Aplicação**: https://automationexercise.com/test_cases

#### Requisitos

- O framework a ser utilizado é o [WebdriverIO](https://webdriver.io/);
- A sintaxe Gherkin NÃO DEVE ser utilizada.

#### Casos de testes

Deve automatizar os seguintes casos de teste. [Link com o passo a passo dos CTs](https://automationexercise.com/test_cases)

- [ ] Test Case 1: Register User
- [ ] Test Case 9: Search Product
- [ ] Test Case 13: Verify Product quantity in Cart
- [ ] Test Case 12: Add Products in Cart
- [ ] Test Case 17: Remove Products From Cart

#### Itens que Serão Avaliados

- O código deve ser de fácil entendimento.
- O código deve seguir um padrão de projeto.
- Execução dos testes em modo headless.
- Testes organizados em suítes.
- Performance de execução dos testes.
- Organização do código, testes e demais arquivos.
- Integração com o relatório Allure Reports.
- Pipeline configurada no GitHub Actions.
- Mapeamento de elementos.
- O arquivo readme.md do projeto deve explicar quais configurações são necessárias, além de como instalar e executar o projeto.

#### Como entregar o desafio

- Criar um repositório no GitHub com o nome `qa.automationexercise-web.webdriverio`
- Enviar o link do repositório público via e-mail

### API

> **API**: https://automationexercise.com/api_list

#### Requisitos

- O framework para desenvolvimento dos testes deve ser o [Pactum JS](https://pactumjs.github.io/)
- A sintaxe Gherkin NÃO DEVE ser utilizada.
- A biblioteca [Joi.dev](https://joi.dev/) deve ser utilizada para validar o schema nos testes de contrato.

#### Casos de testes

Deve automatizar os seguintes casos de teste de API. [Link com o passo a passo dos CTs](https://automationexercise.com/api_list)

##### Realizar TESTE DE CONTRATO para validar os tipos dos campos retornados na resposta dos seguintes CTs:

- [ ] API 1: Get All Products List => Validar somente o status code 200
- [ ] API 12: DELETE METHOD To Delete User Account => Validar somente o status code 200

##### Realizar testes funcionais nos endpoints abaixo.

Obs.: Fique à vontade para realizar as validações que considerar necessárias.

- [ ] API 11: POST To Create/Register User Account
- [ ] API 12: DELETE METHOD To Delete User Account

#### Itens que Serão Avaliados

- O código deve ser de fácil entendimento.
- O código deve seguir um padrão.
- Testes organizados em suítes.
- Performance de execução dos testes.
- Organização do código, testes, pastas e demais arquivos.
- Integração com algum relatório.
- Pipeline configurada no GitHub Actions.
- O arquivo readme.md do projeto deve explicar quais configurações são necessárias, além de como instalar e executar o projeto.
- Para os testes funcionais de API, será avaliado o uso do seu conhecimento teórico para desenvolver os testes.

#### Entregável

- Criar um repositório no GitHub com o nome `qa.automationexercise-api.pactumjs`
- Enviar o link do repositório público via e-mail
