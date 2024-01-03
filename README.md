<h1>principais-comandos-cypress</h1>


<p>O Cypress é uma ferramenta de automação de testes end-to-end (E2E) muito popular para aplicativos da web. Ele fornece uma variedade de comandos que podem ser utilizados para criar testes robustos e eficazes. Abaixo alguns dos principais comandos do Cypress.</p>

1.	cy.visit(): Utilizado para visitar uma URL específica. Por exemplo:
```
cy.visit('https://www.example.com')
```

2.	cy.get(): Seleciona um elemento na página com base em um seletor CSS, permitindo interações com esse elemento, exemplo:
```
cy.get('.classe-do-elemento').click()
```
3.	cy.contains(): Encontra um elemento que contém um texto específico. 	Por exemplo:
```
cy.contains('Botão de Login').click()
```
4.	cy.type(): Insere um texto em um campo de input. Por exemplo:
```
cy.type('#username').type('usuario123')
```
