
# 🧪 Atividade: Testes de Navegação com Cypress

Este exercício tem como objetivo validar a navegação entre páginas da aplicação utilizando o Cypress. Para cada item abaixo, escreva o teste correspondente no Cypress ou execute a verificação manual se solicitado.
Instale todos os módulos do node com:
```bash
   npm install
```
Instale o Cypress com : 

```bash
   npm install cypress 
``` 
Levante o servidor para a apliação REACT ficar disponível.
Faça a configuração inicial com o comando:

```bash
   npx cypress open 
```


---

## ✅ 1. Navegar para a Página 1

- Acesse a página principal do site ("/").
- Clique no link ou botão com o texto "Página 1".
- Verifique se a URL permanece a mesma (ou seja, continua com apenas "/").

---

## ✅ 2. Navegar para a Página 2

- Acesse a página principal do site ("/").
- Clique no link ou botão com o texto "Página 2".
- Verifique se a URL passou a conter o trecho "/page2".

---

## ✅ 3. Navegar para a Página 3

- Acesse a página principal do site ("/").
- Clique no link ou botão com o texto "Página 3".
- Verifique se a URL passou a conter o trecho "/page3".

---

## ✅ 4. Navegar para a página do Carrinho

- Acesse a página principal do site ("/").
- Clique no link ou botão com o texto "Carrinho".
- Verifique se a URL passou a conter o trecho "/cart".

---

💡 Dica: Para todos os testes, utilize os comandos do Cypress como cy.visit(), cy.contains(), e cy.url().should().
