# API-pagamentos
# 💳 API de Pagamentos Segura com Azure

Este projeto demonstra a criação de uma API RESTful voltada para pagamentos, com foco em segurança, controle de acesso e boas práticas de deploy em nuvem utilizando **Microsoft Azure**.

---

## ✅ Objetivos

- Criar uma API funcional que simula transações de pagamento
- Proteger endpoints com autenticação e tokens seguros
- Armazenar chaves de API com segurança no Azure Key Vault
- Realizar deploy e gerenciamento via Azure App Service / API Management

---

## ⚙️ Tecnologias Utilizadas

- Backend: Node.js (Express) ou Python (Flask/FastAPI)
- Azure App Service
- Azure Key Vault
- Azure Active Directory (B2C) ou OAuth2
- Azure API Management (opcional)
- Application Insights

---

## 🔐 Segurança

- 🔑 Tokens e segredos armazenados no Azure Key Vault
- 🔐 Autenticação via Azure AD (Bearer Token)
- 🚫 Acesso limitado por IP e autenticação obrigatória
- 📊 Logs de requisições e erros no Application Insights

---

## 📈 Prints do Projeto

| Descrição                         | Imagem |
|----------------------------------|--------|
| API protegida por Key Vault      | ![](./screenshots/keyvault-config.png) |
| App Service rodando a aplicação  | ![](./screenshots/azure-appservice.png) |
| Azure AD com autenticação ativa  | ![](./screenshots/api-auth.png) |

---

## 🧠 Insights

- Azure Key Vault evita exposição de segredos em código
- O uso do Azure API Management permite controlar taxa de acesso (rate limiting)
- Application Insights ajuda a detectar falhas em tempo real
- Boas práticas de autenticação com Azure AD reforçam a segurança do backend

---

## 🔮 Melhorias Futuras

- Implementar suporte a Webhook para notificações de pagamento
- Registrar logs de transações em Azure Blob Storage
- Criar CI/CD com GitHub Actions e Azure Pipelines

---
