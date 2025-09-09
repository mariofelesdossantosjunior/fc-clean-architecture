# fc-clean-architecture

Projeto de exemplo implementando **Clean Architecture** com **TypeScript** e **Node.js**, inspirado no curso *Full Cycle*.  
O objetivo é demonstrar como estruturar aplicações seguindo boas práticas de separação de responsabilidades e independência de camadas.

---

## 📌 Índice
1. [Descrição](#descrição)  
2. [Arquitetura](#arquitetura)  
3. [Tecnologias Utilizadas](#tecnologias-utilizadas)  
4. [Funcionalidades](#funcionalidades)  
5. [Instalação e Execução](#instalação-e-execução)  
6. [Estrutura de Pastas](#estrutura-de-pastas)  
7. [Testes](#testes)  
8. [Contribuição](#contribuição)  
9. [Licença](#licença)  

---

## 📖 Descrição
Este projeto aplica o padrão **Clean Architecture**, separando claramente as responsabilidades em camadas como **Domain**, **Use Cases**, **Infrastructure** e **Presentation**.  
Essa abordagem facilita testes, manutenção e escalabilidade.

---

## 🏛 Arquitetura
- **Domain** – Entidades e regras de negócio puras.  
- **Use Cases** – Casos de uso que representam ações da aplicação.  
- **Infrastructure** – Implementações de repositórios, banco de dados e integrações externas.  
- **Presentation** – Entrada/saída da aplicação, como rotas HTTP (controllers).  

---

## 🛠 Tecnologias Utilizadas
- **Node.js**  
- **TypeScript**  
- **Express** (API REST)  
- **Sequelize** (ORM)  
- **SQLite** (banco de dados em memória para testes)  
- **Jest** (testes unitários e integração)  
- **Supertest** (testes de endpoints)  

---

## ⚙️ Funcionalidades
- Criação e listagem de produtos (exemplo prático).  
- Estrutura modular seguindo Clean Architecture.  
- Testes unitários e de integração configurados.  
- Banco em memória para testes automáticos.  

---

## 🚀 Instalação e Execução

```bash
# 1. Clone o repositório
git clone https://github.com/mariofelesdossantosjunior/fc-clean-architecture.git
cd fc-clean-architecture

# 2. Instale as dependências
npm install

# 3. Execute a aplicação
npm run start

# 4. Execute em modo de desenvolvimento
npm run dev

# 5. Execute os testes
npm test

```
---
## 📂 Estrutura de Pastas
<img width="618" height="237" alt="image" src="https://github.com/user-attachments/assets/bd35b825-6ae8-47f0-bd0b-793315462e5b" />

---

🧪 Testes
O projeto utiliza Jest e Supertest.
Para rodar os testes:

```bash
npm test
```

---

📜 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

