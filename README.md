# App de Autenticação — React Native + Firebase

Aplicativo mobile com **cadastro, login e logout** usando Firebase Authentication.

## Funcionalidades

- Tela de cadastro (nome, e-mail e senha)
- Tela de login (e-mail e senha)
- Tela inicial com opção de sair
- Navegação entre telas com React Navigation

## Tecnologias

React Native · Expo · Firebase Authentication · React Navigation

## Como executar

1. Instale as dependências: `npm install`
2. Copie `.env.example` para `.env` e preencha com as credenciais do **seu** projeto Firebase
3. Rode `npm start` e abra no Expo Go, ou use `npm run web`

## Estrutura

```text
├── App.js
├── app.config.js          # lê as variáveis do .env
├── config/
│   └── firebaseConfig.js
├── telas/
│   ├── TelaLogin.js
│   ├── TelaCadastro.js
│   └── TelaHome.js
└── assets/
```
