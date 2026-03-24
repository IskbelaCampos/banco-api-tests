# Banco API Tests

## 📌 Objetivo

Este projeto tem como objetivo automatizar os testes da API REST do projeto [banco-api](https://github.com/juliodelimas/banco-api), contribuindo para a qualidade e confiabilidade dos endpoints por meio de testes automatizados.

A automação cobre cenários de sucesso e falha, validando respostas HTTP, estrutura de dados e regras de negócio da API.

---

## 🚀 Stack Utilizada

- **JavaScript (Node.js)**
- **Mocha** – Framework de testes
- **Chai** – Biblioteca de asserções
- **Supertest** – Testes de API HTTP
- **Mochawesome** – Geração de relatórios em HTML
- **dotenv** – Gerenciamento de variáveis de ambiente

---

## 📁 Estrutura de Diretórios

banco-api-tests/
│
├── test/                # Arquivos de testes automatizados
|    ├── login.test.js
|    └── transferencia.test.js
├── mochawesome/         # Relatórios gerados em HTML
├── node_modules/        # Dependências do projeto
├── .env                 # Variáveis de ambiente (não versionado)
├── .gitignore
├── package.json
└── README.md

---

## ⚙️ Configuração do Ambiente

### 1. Clonar o repositório

git clone https://github.com/IskbelaCampos/banco-api-tests.git  
cd banco-api-tests

### 2. Instalar dependências

npm install

---

## 🔐 Configuração do arquivo .env

Crie um arquivo `.env` na raiz do projeto com o seguinte conteúdo:

BASE_URL=http://localhost:3000

> ⚠️ O valor da BASE_URL deve apontar para a API em execução

---

## ▶️ Execução dos Testes

npm test

---

## 📊 Geração de Relatórios

Os relatórios são gerados automaticamente na pasta:

mochawesome/

Abra no navegador:

mochawesome/mochawesome.html

---

## 📚 Documentação das Dependências

- Mocha: https://mochajs.org/
- Chai: https://www.chaijs.com/
- Supertest: https://github.com/ladjs/supertest
- Mochawesome: https://github.com/adamgruber/mochawesome
- dotenv: https://github.com/motdotla/dotenv

---

## 📄 Licença

Projeto para fins educacionais.
EOF
