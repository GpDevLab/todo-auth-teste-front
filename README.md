# ✅ Lista de Tarefas com Autenticação

Desafio de desenvolvimento fullstack com **Next.js** e **TailwindCSS**. O objetivo é criar uma aplicação web de gerenciamento de tarefas com autenticação segura e design moderno.

## 🎯 Objetivo

Desenvolver uma aplicação que:
- ✅ Permita o cadastro e login de usuários
- ✅ Liste, adicione, edite e remova tarefas (CRUD)
- ✅ Garanta que cada usuário visualize apenas suas tarefas
- ✅ Tenha uma interface responsiva e bonita

---

## 🚀 Como rodar a API
Instale o JSON Server (caso ainda não tenha)
- npm install -g json-server
- git clone https://github.com/GpDevLab/todo-auth-teste-front
- cd server
- json-server --watch db.json --port 3001
- A API estará acessível em http://localhost:3001

## 📌 Requisitos Técnicos

### **Obrigatórios**
- ✅ **Next.js** (versão 13 ou superior)
- ✅ **TailwindCSS** para estilização
- ✅ **Autenticação** via credenciais ou com NextAuth.js

### **Desejáveis (Bônus)**
- 🧪 **Testes unitários** com Jest/RTL
- 🎨 **Dark/Light Mode**
- 🔐 Middleware de proteção de rotas
- 📱 App responsivo e com animações

---

## 🚀 Funcionalidades Principais

### **1. Autenticação de Usuário**
- Registro e login com email/senha
- Sessão persistente com JWT ou cookies (NextAuth)
- Redirecionamento de páginas seguras

### **2. CRUD de Tarefas**
- Criar tarefas com título e descrição
- Editar e excluir tarefas
- Visualizar tarefas em cards ou listas
- Armazenamento no banco vinculado ao usuário

### **3. UI Responsiva**
- Interface moderna com TailwindCSS
- Feedback visual para ações (ex: toast de sucesso)
- Layout simples e intuitivo

---

## ✨ Sugestões de Melhorias (Bônus)

- 🔔 Notificações de tarefas
- ⏰ Agendamento com datas e horários
- 📊 Filtro por status (feito/pendente)
- 👥 Múltiplos usuários com permissões
- ☁️ Deploy com banco remoto (ex: Supabase, PlanetScale)

---

## 📌 Regras de Entrega

- ✅ Subir projeto no GitHub (público)
- ✅ README com:
  - 📦 Instruções de instalação
  - 💡 Decisões técnicas
  - 🚧 Dificuldades e aprendizados

---

## 📎 Links Úteis

- 🔗 [Next.js](https://nextjs.org/)
- 🎨 [TailwindCSS](https://tailwindcss.com/)
- 🔐 [NextAuth.js](https://next-auth.js.org/)

Boa sorte! 🚀 Dê seu melhor e divirta-se desenvolvendo! 🧠🛠️
