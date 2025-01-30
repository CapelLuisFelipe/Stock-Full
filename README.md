# 📦 Estoque Dev

**Estoque Dev** é um sistema de gerenciamento de estoque que permite cadastrar, visualizar e gerenciar produtos, incluindo operações de compra e venda. Desenvolvido com **React, TypeScript, Node.js e Prisma**, ele fornece uma interface moderna e intuitiva para controle eficiente de estoque.

---

## 🚀 Tecnologias Utilizadas

- ⚛️ **Frontend:** React, TypeScript, Vite, Tailwind CSS
- 🖥️ **Backend:** Node.js, Express, Prisma
- 🗄️ **Banco de Dados:** SQLite (pode ser adaptado para PostgreSQL ou MySQL)
- 🌐 **Deploy:** Vercel e Railway (ou semelhante)

---

## 📷 Demonstração
<img width="1470" alt="Captura de Tela 2025-01-30 às 00 48 54" src="https://github.com/user-attachments/assets/686c5012-6f44-41bf-839f-55055ac277ca" />


Interface moderna e responsiva para facilitar o gerenciamento de produtos no estoque.

---

## 📌 Funcionalidades

✅ **Cadastro de Produtos** – Adicione novos produtos ao estoque com nome, descrição, quantidade e preço.  
✅ **Listagem de Produtos** – Visualize todos os produtos cadastrados em uma interface organizada.  
✅ **Compra e Venda** – Registre transações de compra e venda diretamente no sistema.  
✅ **Remoção de Produtos** – Exclua itens do estoque com apenas um clique.  
✅ **Banco de Dados Relacional** – Utiliza Prisma ORM para facilitar o gerenciamento dos dados.  

---

## 🛠️ Como Rodar o Projeto Localmente

### **1️⃣ Clone o repositório**
```sh
git clone https://github.com/seu-usuario/estoque-dev.git
cd estoque-dev
```

### **2️⃣ Configure o Backend**
```sh
cd backend
npm install
cp .env.example .env   # Configure o banco de dados no arquivo .env
npx prisma migrate dev  # Executa as migrações no banco de dados
npm run dev
```

### **3️⃣ Configure o Frontend**
Abra outro terminal e execute:
```sh
cd frontend
npm install
npm run dev
```
Acesse no navegador: `http://localhost:5173`

---

## 🎯 Melhorias Futuras

- [ ] Adicionar autenticação de usuários (JWT/Auth0)
- [ ] Implementar filtros de busca e ordenação
- [ ] Criar dashboard com gráficos de movimentação do estoque
- [ ] Melhorar o design e responsividade

---

## 📜 Licença

Este projeto está sob a licença **MIT**. Sinta-se à vontade para utilizá-lo e contribuir! 🚀

## 📞 Contato

Desenvolvido por **Luis Felipe Capel**. Entre em contato comigo:

[![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CapelLuisFelipe)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/luis-felipe-capel-832251249/)  
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/luis.felipe.capel/)  

