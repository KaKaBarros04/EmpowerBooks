# 📚 Empower Books — Online Bookstore System

**Empower Books** is an online bookstore developed as a final project for a web programming course, focusing on **backend**, **business rules**, and **database integration**.

The system simulates a real-world e-commerce scenario, allowing for the management of users, books, orders, and reviews.

---

## 🔍 Overview

The platform allows users to:

- Explore and search for books using different criteria
- Make online purchases
- Track orders and purchase history
- View book details (author, synopsis, and reviews)

In addition, the system has an **administrative area** for complete bookstore management.

---

## ✨ Features

### 👤 User
- User registration and login
- Profile management
- Order history
- Book ratings and comments

### 📚 Books
- Book listing by category
- Search by title, author, and keywords
- View book details

### 🛒 Purchases
- Shopping cart
- Order completion
- Order tracking

### ⚙️ Administration
- Book and category management
- Inventory control
- Order management

---

## 🔌 REST API

The system has an integrated REST API, responsible for communication between the front-end and the database.

### API Features
- User authentication
- Access control (admin / user)
- CRUD for books
- CRUD for orders
- Data persistence with MySQL

---

## 🔐 Controle de Acesso

O sistema possui níveis de acesso:
- **Administrador**: gerencia livros, categorias, estoque e pedidos
- **Usuário**: realiza compras, avalia livros e acompanha pedidos

---
 
## 🛠️ Technologies Used

### Front-end
- HTML5
- CSS3
- JavaScript
- Bootstrap

### Back-end
- PHP
- MySQL

### Other
- XAMPP / WAMP (local environment)
- Git & GitHub (version control)

---

## ▶️ Installation and Configuration

### 1️⃣ Clone the repository
```bash
git clone https://github.com/KaKaBarros04/EmpowerBooks.git
```



2️⃣ Configure o banco de dados

Crie um banco de dados no MySQL chamado empower_books

Importe o arquivo:
```bash
banco_de_dados/dados_livraria.sql
```



3️⃣ Configure a conexão com o banco

No arquivo conexao.php, ajuste as credenciais:
```bash
$host = "localhost";
$user = "root";      // Usuário do MySQL
$password = "";      // Senha do MySQL
$database = "empower_books";

$dbc = mysqli_connect($host, $user, $password, $database);
```



4️⃣ Inicie o servidor

Inicie o Apache e o MySQL (XAMPP/WAMP)

Acesse no navegador:
```bash
http://localhost/empower_books/
```

---

📚 Aprendizados

Neste projeto foram praticados conceitos como:

Autenticação de usuários em PHP

Operações CRUD com MySQL

Organização de código backend

Regras de negócio para e-commerce

Versionamento com Git e GitHub

---

🔮 Melhorias Futuras

Implementação de sistema de cupons de desconto

Melhoria da interface da área administrativa

Criação de uma API REST para integração com outras plataformas

Implementação de níveis de acesso (admin / usuário)

---


👨‍💻 Autor

Desenvolvido por Kauan Benitez

📧 Email: kauan.dev4@gmail.com

📱 WhatsApp: +351 935610979

🌐 GitHub: https://github.com/KaKaBarros04

---


📜 Licença

Este projeto está licenciado sob a MIT License.

---

⭐ Se gostou do projeto, deixe uma estrela e fique à vontade para contribuir!
