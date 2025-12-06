# 🚀 API de Gerenciamento de Tarefas - Módulo 5

## 📌 Sobre o Projeto

API RESTful completa desenvolvida com **Node.js**, **Express** e **MongoDB** para gerenciamento de tarefas com autenticação JWT.

✅ Todos os requisitos do Módulo 5 implementados
✅ Pronta para deploy no Render
✅ Documentação completa
✅ Testes incluídos

---

## 📚 DOCUMENTAÇÃO COMPLETA

### 🎯 Começar Aqui:
1. **[ENTREGA-MODULO-5.md](ENTREGA-MODULO-5.md)** - ⭐ Leia primeiro! Visão geral completa do projeto
2. **[GUIA-DEPLOY-RENDER.md](GUIA-DEPLOY-RENDER.md)** - 📖 Guia passo a passo completo para deploy
3. **[COMANDOS-RAPIDOS.md](COMANDOS-RAPIDOS.md)** - ⚡ Referência rápida de comandos

### 📖 Documentação Técnica:
- **[API-README.md](API-README.md)** - Documentação completa dos endpoints da API
- **[DIAGRAMA-API.md](DIAGRAMA-API.md)** - Diagramas e arquitetura visual
- **[TESTAR-LOCALMENTE.md](TESTAR-LOCALMENTE.md)** - Como testar a API localmente
- **[EXEMPLOS-TESTE.md](EXEMPLOS-TESTE.md)** - Exemplos prontos para copiar e colar

### 🔧 Arquivos de Configuração:
- **[.env.example](.env.example)** - Exemplo de variáveis de ambiente
- **[thunder-collection.json](thunder-collection.json)** - Coleção Thunder Client/Postman
- **[package.json](package.json)** - Dependências do projeto

---

## 🏗️ Estrutura do Projeto

```
Projeto-3-main/
│
├── 📂 models/              # Modelos MongoDB
│   ├── User.js            # Schema de usuário
│   └── Tarefa.js          # Schema de tarefa
│
├── 📂 routes/              # Rotas da API
│   ├── auth.js            # Autenticação (register, login)
│   ├── usuarios.js        # Listar usuários
│   └── tarefas.js         # CRUD de tarefas
│
├── 📂 middleware/          # Middlewares
│   └── auth.js            # Verificação JWT
│
├── 📄 server.js            # Servidor Express
├── 📄 package.json         # Dependências
├── 📄 .env                 # Variáveis de ambiente (local)
├── 📄 .gitignore           # Arquivos ignorados
│
└── 📂 docs/                # Documentação completa
    ├── ENTREGA-MODULO-5.md
    ├── GUIA-DEPLOY-RENDER.md
    ├── API-README.md
    ├── DIAGRAMA-API.md
    ├── TESTAR-LOCALMENTE.md
    ├── EXEMPLOS-TESTE.md
    └── COMANDOS-RAPIDOS.md
```

---

## ✅ Endpoints Implementados

### 🔓 Públicos (Sem autenticação)
- `GET /` - Informações da API
- `POST /auth/register` - Registrar usuário
- `POST /auth/login` - Login (retorna JWT)
- `GET /usuarios` - Listar usuários

### 🔒 Protegidos (Requer JWT)
- `POST /tarefas` - Criar tarefa
- `GET /tarefas` - Listar tarefas do usuário
- `GET /tarefas/:id` - Buscar tarefa
- `PUT /tarefas/:id` - Atualizar tarefa
- `DELETE /tarefas/:id` - Excluir tarefa

---

## 🛠️ Tecnologias

- **Node.js** - Runtime JavaScript
- **Express** - Framework web
- **MongoDB** - Banco de dados NoSQL
- **Mongoose** - ODM para MongoDB
- **JWT** - Autenticação
- **BCryptjs** - Criptografia de senhas
- **CORS** - Cross-Origin Resource Sharing

---

## 🚀 Como Usar

### Opção 1: Deploy no Render (Recomendado)
Siga o guia completo: [GUIA-DEPLOY-RENDER.md](GUIA-DEPLOY-RENDER.md)

### Opção 2: Rodar Localmente
1. Configure MongoDB Atlas
2. Copie `.env.example` para `.env`
3. Edite `.env` com suas credenciais
4. Execute:
```bash
npm install
npm start
```

---

## 📦 Instalação Rápida

```bash
# Instalar dependências
npm install

# Iniciar servidor
npm start

# Servidor rodará em http://localhost:5000
```

---

## 🧪 Testar a API

### Usando Thunder Client (VS Code)
1. Instale a extensão Thunder Client
2. Importe `thunder-collection.json`
3. Configure as variáveis de ambiente
4. Execute as requisições

### Exemplos Prontos
Consulte [EXEMPLOS-TESTE.md](EXEMPLOS-TESTE.md) para exemplos completos com curl/Postman.

---

## 🔐 Segurança

✅ Senhas criptografadas com bcryptjs
✅ Autenticação JWT com expiração
✅ Middleware de proteção de rotas
✅ Validação de dados com Mongoose
✅ Usuários isolados (cada um vê apenas suas tarefas)

---

## 📋 Checklist de Requisitos

- [x] API com Node.js + Express
- [x] Banco MongoDB conectado
- [x] Registro de usuário
- [x] Login retorna JWT
- [x] CRUD completo de tarefas
- [x] Rotas protegidas com JWT
- [x] Listar usuários
- [x] Segurança implementada
- [x] Pronta para deploy no Render

---

## 🎓 Entrega

**O que entregar:**
✅ Apenas o link da API publicada no Render

Exemplo: `https://api-tarefas.onrender.com`

---

## 📞 Links Úteis

- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- [Render](https://render.com)
- [Node.js](https://nodejs.org)
- [Express](https://expressjs.com)

---

## 🎉 Status

✅ **PROJETO COMPLETO E PRONTO PARA ENTREGA**

- Código funcionando ✅
- Documentação completa ✅
- Testes incluídos ✅
- Guias de deploy ✅
- Segurança implementada ✅

---

## 👨‍💻 Desenvolvimento

Projeto desenvolvido para o Módulo 5 - Desenvolvimento Back-end com Node.js, Express e MongoDB.

---

**Boa sorte com a entrega! 🚀**
