# ⚙️ Automação de Testes

Esta pasta reúne os projetos de automação de testes desenvolvidos com **Cypress + JavaScript**.

O objetivo é demonstrar minha capacidade de **automatizar fluxos críticos** de aplicações web, aplicando boas práticas de organização, legibilidade e manutenibilidade de código de teste.

---

## 📂 Estrutura da Pasta

```
automacao/
├── cypress/
│   ├── e2e/
│   ├── fixtures/
│   └── support/
├── cypress.config.js
└── package.json
```

---

### 🧪 Testes E2E
📁 [`/cypress/e2e`](./cypress/e2e)

Cenários de teste automatizados cobrindo os principais fluxos da aplicação:

- ✅ Fluxos críticos (login, cadastro, compra, etc.)
- ❌ Cenários negativos (credenciais inválidas, campos obrigatórios, etc.)
- 🔲 Edge cases

---

### 📦 Fixtures
📁 [`/cypress/fixtures`](./cypress/fixtures)

Arquivos de massa de dados utilizados nos testes:

- 👤 Dados de usuários
- 📋 Payloads reutilizáveis entre cenários

---

### 🛠️ Support
📁 [`/cypress/support`](./cypress/support)

Configurações e comandos customizados do Cypress:

- 🔧 Comandos reutilizáveis (`cy.login()`, etc.)
- ⚙️ Configurações globais de execução

---

## 🛠️ Ferramentas Utilizadas

![Cypress](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

---

## ▶️ Como Executar

```bash
# Instalar dependências
npm install

# Abrir interface do Cypress
npx cypress open

# Executar testes no modo headless
npx cypress run
```

---

## 🎯 Objetivo

Garantir a **confiabilidade dos fluxos principais** da aplicação por meio de testes automatizados, reduzindo esforço de regressão manual e aumentando a velocidade de feedback no ciclo de desenvolvimento.

> 📌 Os conteúdos desta pasta são atualizados conforme a evolução dos estudos e projetos práticos em QA.
