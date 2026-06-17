# 🚀 QR Code & Password Generator

Kit de utilidades desenvolvido em **Node.js** para geração de **QR Codes** e **senhas personalizadas** através do terminal.

Este projeto foi desenvolvido durante um desafio prático da **DIO (Digital Innovation One)** com o objetivo de aplicar conceitos de modularização, organização de código, gerenciamento de dependências e utilização de bibliotecas externas.

---

## 📖 Sobre o Projeto

A aplicação oferece uma interface interativa no terminal onde é possível selecionar diferentes ferramentas, como:

* Geração de QR Codes;
* Geração de senhas personalizadas.

A arquitetura foi organizada em módulos independentes, facilitando a manutenção do código e permitindo a adição de novas funcionalidades no futuro.

---

## 🛠️ Tecnologias Utilizadas

* Node.js
* JavaScript
* NPM
* Dotenv
* QRCode
* Prompt

---

## 📂 Estrutura do Projeto

```text
projeto-qrcode/
│
├── assets/
│   └── demo-qrcode.png
│
├── src/
│   ├── prompts-schema/
│   │   ├── prompt-schema-main.js
│   │   └── prompt-schema-qrcode.js
│   │
│   ├── services/
│   │   ├── password/
│   │   │   ├── utils/
│   │   │   │   └── permitted-characters.js
│   │   │   ├── create.js
│   │   │   └── handle.js
│   │   │
│   │   └── qr-code/
│   │       ├── create.js
│   │       └── handle.js
│   │
│   └── index.js
│
├── .env
├── package.json
├── package-lock.json
└── README.md
```

---

## ⚙️ Instalação

Clone o repositório:

```bash
git clone https://github.com/SEU-USUARIO/projeto-qrcode.git
```

Acesse a pasta do projeto:

```bash
cd projeto-qrcode
```

Instale as dependências:

```bash
npm install
```

---

## ▶️ Executando o Projeto

```bash
npm start
```

ou

```bash
node --env-file=.env src/index.js
```

---

## 🎯 Funcionalidades

### QR Code

* Geração de QR Codes a partir de textos ou URLs;
* Exibição diretamente no terminal;
* Opção de personalização do formato de saída.

### Password Generator

* Criação de senhas aleatórias;
* Utilização de conjuntos de caracteres configuráveis;
* Estrutura preparada para futuras melhorias.

---

## 📸 Demonstração

### Gerando um QR Code pelo terminal

O usuário seleciona a ferramenta desejada, informa o conteúdo que será convertido e escolhe o formato de saída.

![Demonstração do projeto](./assets/demo-qrcode.png)

---

## 📚 Conceitos Praticados

Durante o desenvolvimento deste projeto foram aplicados conceitos como:

* Modularização de aplicações Node.js;
* Separação de responsabilidades;
* Organização de código por camadas;
* Utilização de dependências externas;
* Manipulação de entrada de dados via terminal;
* Configuração de variáveis de ambiente;
* Estruturação de projetos escaláveis.

---

## 🎓 Objetivo de Aprendizagem

O foco deste projeto foi praticar a construção de aplicações Node.js organizadas em módulos reutilizáveis, compreendendo melhor a integração de bibliotecas externas e a estruturação de sistemas de forma escalável.

---

## 👨‍💻 Autor

**Jefferson Pereira Salvador**

Estudante de Engenharia de Software com foco em desenvolvimento backend, bancos de dados e construção de aplicações escaláveis.

---

Projeto desenvolvido para fins educacionais através da plataforma DIO.
