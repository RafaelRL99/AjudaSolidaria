# AjudaSolidária

Plataforma web desenvolvida para facilitar o gerenciamento de doações e solicitações entre doadores, beneficiários e organizações sociais.

---

## 🎯 Objetivo

Oferecer uma solução simples onde usuários podem:

- Cadastrar doações de itens
- Solicitar ajuda
- Visualizar e gerenciar registros com controle de acesso

---

## ⚙️ Tecnologias utilizadas

- PHP 8
- MySQL
- HTML + CSS
- XAMPP (Apache + MySQL)
- Git / GitHub

---

## 📁 Estrutura principal

```
/ajuda_solidaria
├── login.php / logout.php / dashboard.php
├── conexao.php / session_check.php
├── /usuarios         (CRUD de usuários)
├── /solicitacoes     (CRUD de solicitações)
├── listar_itens.php  (CRUD de itens)
├── ajuda_solidaria_banco.sql
```

---

## ▶️ Como executar

1. Copie o projeto para a pasta `htdocs` do XAMPP
2. Importe o arquivo `ajuda_solidaria_banco.sql` no phpMyAdmin
3. Acesse: [http://localhost/ajuda_solidaria](http://localhost/ajuda_solidaria)

---

## 👤 Login de exemplo

Você pode criar um usuário do tipo "Doador", "Beneficiário" ou "Organização" usando o cadastro do sistema.

---

## 📌 Observações

- Projeto desenvolvido como parte do tema integrador do curso GPAUni (CDC 2025)
- Inspirado no ODS 17 da ONU: Parcerias e meios de implementação