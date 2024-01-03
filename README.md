<h1>Principais Comandos Cypress</h1>


<p>O Cypress é uma ferramenta de automação de testes end-to-end (E2E) muito popular para aplicativos da web. Ele fornece uma variedade de comandos que podem ser utilizados para criar testes robustos e eficazes. Abaixo alguns dos principais comandos do Cypress.</p>

1.	cy.visit(): Utilizado para visitar uma URL específica. Por exemplo:
```
cy.visit('https://www.example.com')
```

2.	cy.get(): Seleciona um elemento na página com base em um seletor _CSS_, permitindo interações com esse elemento, exemplo:
```
cy.get('.classe-do-elemento').click()
```
3.	cy.contains(): Encontra um elemento que contém um texto específico. 	Por exemplo:
```
cy.contains('Botão de Login').click()
```
4.	cy.type(): Insere um texto em um campo de input. Por exemplo:
```
cy.get('#username').type('usuario123')
```
5.	cy.click(): Clica em um elemento na página. Exemplo:
```
cy.get('.botao-submit').click()
```
6.	cy.reload(): Recarrega a página. Por exemplo:
```
cy.reload()
```
7.	cy.wait(): Espera um determinado período de tempo ou por uma condição específica. Por exemplo, para esperar dois segundos:
```
cy.wait(2000)
```
8.	cy.fixture(): Carrega dados de um arquivo de fixture. Exemplo:
```
cy.fixture('dados.json').then((dados) => {
  // Utilize os dados carregados aqui
})
```
9.	cy.intercept(): Controla requisições de rede. Permite _mockar_ ou modificar comportamentos de requisições HTTP. Por exemplo:
 ```
cy.intercept('GET', '/api/endpoint', { statusCode: 200, body: 'Mocked response' })
```
<p>Estes são apenas alguns dos principais comandos do Cypress. O Cypress oferece uma gama completa de funcionalidades e comandos para automatizar e testar aplicativos da web de forma eficiente e robusta. </p>

[Documentação Oficial Cypress](https://docs.cypress.io/guides/overview/why-cypress) 

<P>"Mockar" é uma prática no desenvolvimento de software na qual são criadas simulações de partes do sistema real, como funções, classes, APIs ou dependências externas, para serem usadas durante testes automatizados. Essas simulações, chamadas de "mocks", permitem isolar o código em teste, eliminando dependências externas e controlando o ambiente de teste. O objetivo é garantir que os testes se concentrem na unidade de código específica, tornando-os mais previsíveis, rápidos e independentes de fatores externos, como a disponibilidade ou comportamento real de sistemas externos.</P>


