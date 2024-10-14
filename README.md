# Desafio Técnico Teórico

**Prazo do desafio**: 3 dias a partir do recebimento do e-mail.

## WEB

> **Aplicação**: https://automationexercise.com/test_cases

### Requisitos

- O framework a ser utilizado é o [WebdriverIO](https://webdriver.io/);
- A sintaxe Gherkin NÃO DEVE ser utilizada.

### Casos de testes

Deve automatizar os seguintes casos de teste. [Link com o passo a passo dos CTs](https://automationexercise.com/test_cases)

- [ ] Test Case 1: Register User
- [ ] Test Case 9: Search Product
- [ ] Test Case 13: Verify Product quantity in Cart
- [ ] Test Case 12: Add Products in Cart
- [ ] Test Case 17: Remove Products From Cart

### Itens que Serão Avaliados

- O código deve ser de fácil entendimento.
- O código deve seguir um padrão.
- Execução dos testes em modo headless.
- Testes organizados em suítes.
- Performance de execução dos testes.
- Organização do código, testes e demais arquivos.
- Integração com o relatório Allure Reports.
- Pipeline configurada no GitHub Actions.
- Mapeamento de elementos.
- O arquivo readme.md do projeto deve explicar quais configurações são necessárias, além de como instalar e executar o projeto.

### Como entregar o desafio

- Criar um repositório no GitHub com o nome 'qa.automationexercise-web.webdriverio'
- Enviar o link do repositório público via e-mail

## API

> **API**: https://automationexercise.com/api_list

### Requisitos

- O framework para desenvolvimento dos testes deve ser o [Pactum JS](https://pactumjs.github.io/)
- A sintaxe Gherkin NÃO DEVE ser utilizada.
- A biblioteca [Joi.dev](https://joi.dev/) deve ser utilizada para validar o schema nos testes de contrato.

### Casos de testes

Deve automatizar os seguintes casos de teste de API. [Link com o passo a passo dos CTs](https://automationexercise.com/api_list)

#### Realizar TESTE DE CONTRATO para validar os tipos dos campos retornados na resposta dos seguintes CTs:

- [ ] API 1: Get All Products List => Validar somente o status code 200
- [ ] API 12: DELETE METHOD To Delete User Account => Validar somente o status code 200

#### Realizar testes funcionais nos endpoints abaixo.

Obs.: Fique à vontade para realizar as validações que considerar necessárias.

- [ ] API 11: POST To Create/Register User Account
- [ ] API 12: DELETE METHOD To Delete User Account

### Itens que Serão Avaliados

- O código deve ser de fácil entendimento.
- O código deve seguir um padrão.
- Testes organizados em suítes.
- Performance de execução dos testes.
- Organização do código, testes, pastas e demais arquivos.
- Integração com algum relatório.
- Pipeline configurada no GitHub Actions.
- O arquivo readme.md do projeto deve explicar quais configurações são necessárias, além de como instalar e executar o projeto.
- Para os testes funcionais de API, será avaliado o uso do seu conhecimento teórico para desenvolver os testes.

### Entregável

- Criar um repositório no GitHub com o nome 'qa.automationexercise-api.pactumjs'
- Enviar o link do repositório público via e-mail
