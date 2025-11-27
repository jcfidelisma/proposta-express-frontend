# Proposta Express - Frontend

Este é o frontend do sistema **Proposta Express**, desenvolvido em HTML, CSS e JavaScript.  
Ele se conecta ao backend hospedado no Render para envio de propostas comerciais em PDF por e-mail e consulta de histórico.

## 🚀 Funcionalidades
- Formulário para envio de propostas comerciais.
- Geração automática de PDF e envio por e-mail (via backend).
- Consulta de histórico de propostas enviadas.
- Interface responsiva com Bootstrap.

## 🌐 Deploy
O frontend é publicado via **GitHub Pages**.  
Após o deploy, estará disponível em: https://jcfidelisma.github.io/proposta-express-frontend/

## 🔗 Integração com Backend
O frontend consome a API hospedada no Render:

- `POST /send-email` → Envia proposta e gera PDF.  
- `GET /propostas` → Lista histórico de propostas.  

Backend: [proposta-express-backend](https://github.com/jcfidelisma/proposta-express-backend)

## 📂 Estrutura
proposta-express-frontend/
│── index.html # Página principal (formulário de envio)
│── historico.html # Página de histórico de propostas
│── index.js # Scripts auxiliares
│── README.md # Documentação

## 🛠️ Tecnologias
- HTML5
- CSS3
- JavaScript
- Bootstrap 5
---
✍️ Desenvolvido por João Carlos Fidelis de Moura Affonso
