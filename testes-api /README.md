# 🔌 Testes de API

Esta pasta reúne os testes de API realizados nos projetos de estudo deste portfólio, utilizando o **Postman** como principal ferramenta.

O objetivo é demonstrar minha capacidade de **validar serviços REST**, verificando comportamento, contrato e integridade dos dados retornados pelas APIs.

---

## 📂 Estrutura da Pasta

```
testes-api/
├── collections/
├── environments/
└── relatorios/
```

---

### 📦 Collections
📁 [`/collections`](./collections)

Coleções do Postman exportadas em `.json`, organizadas por projeto/funcionalidade:

- 🔁 Requisições GET, POST, PUT, PATCH e DELETE
- ✅ Validações de status code
- 📄 Validações de contrato (schema)
- 🔍 Validações de dados no corpo da resposta

---

### 🌐 Environments
📁 [`/environments`](./environments)

Arquivos de ambiente do Postman para facilitar a troca entre contextos:

- 🧪 Ambiente de desenvolvimento
- 🚀 Ambiente de produção/homologação

---

### 📊 Relatórios
📁 [`/relatorios`](./relatorios)

Resultados das execuções dos testes de API:

- 📌 Sumário de execução
- ❌ Falhas encontradas e descrição
- 📈 Taxa de cobertura dos endpoints testados

---

## 🛠️ Ferramentas Utilizadas

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![REST API](https://img.shields.io/badge/REST-API-005571?style=for-the-badge)

---

## 🎯 Objetivo

Validar que os endpoints da API funcionam conforme o esperado — verificando **status codes, contratos, dados e comportamento** em cenários positivos, negativos e de borda.

> 📌 Os conteúdos desta pasta são atualizados conforme a evolução dos estudos e projetos práticos em QA.
