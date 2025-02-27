### README - CRUD com Laravel, PHP, XAMPP e MySQL

---

# CRUD com Laravel  

Este é um projeto de **CRUD (Create, Read, Update, Delete)** desenvolvido em **Laravel**, utilizando **PHP**, **XAMPP** como servidor local e **MySQL** como banco de dados.

---

## 🎯 Objetivo  

O projeto tem como objetivo demonstrar a criação de um sistema simples de CRUD para gerenciar registros, utilizando as boas práticas do Laravel e facilitando a manipulação de dados no banco de dados.

---

## 🛠️ Tecnologias Utilizadas  

- **PHP**: Linguagem de programação para desenvolvimento backend.  
- **Laravel**: Framework PHP para desenvolvimento ágil e estruturado.  
- **XAMPP**: Servidor local com Apache e MySQL.  
- **MySQL**: Banco de dados relacional.  
- **Composer**: Gerenciador de dependências do PHP.  

---

## 📂 Estrutura do Projeto  

```plaintext
.
├── app/           # Contém os arquivos principais do Laravel (Modelos, Controladores, etc.)
├── database/      # Migrações e seeds do banco de dados.
├── public/        # Arquivos acessíveis pelo navegador (index.php, assets, etc.)
├── resources/     # Views (Blade templates) e arquivos frontend.
├── routes/        # Arquivo de rotas (web.php).
├── .env           # Arquivo de configuração do ambiente.
├── composer.json  # Arquivo de dependências do Composer.
└── README.md      # Documentação do projeto.
```

---

## 🚀 Funcionalidades  

- **Create:** Cadastro de novos registros.  
- **Read:** Exibição de uma lista de registros armazenados no banco de dados.  
- **Update:** Edição de registros existentes.  
- **Delete:** Exclusão de registros.  

---

## 📦 Pré-requisitos  

1. **XAMPP** instalado e configurado.  
2. **Composer** instalado no sistema.  
3. **Laravel** configurado globalmente ou via Composer.  
4. Servidor MySQL em execução.

---

## 🛠️ Como Configurar o Projeto  

### 1. Clone o Repositório
```bash
git clone https://github.com/seu-usuario/crud-laravel.git
```

### 2. Acesse a Pasta do Projeto
```bash
cd crud-laravel
```

### 3. Instale as Dependências do Laravel
```bash
composer install
```

### 4. Configure o Ambiente
Edite o arquivo `.env` e configure as informações de acesso ao banco de dados:
```dotenv
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nome_do_banco
DB_USERNAME=seu_usuario
DB_PASSWORD=sua_senha
```

### 5. Crie o Banco de Dados
No MySQL, crie um banco de dados para o projeto:
```sql
CREATE DATABASE nome_do_banco;
```

### 6. Execute as Migrações
```bash
php artisan migrate
```

### 7. Inicie o Servidor Local
```bash
php artisan serve
```

O servidor será iniciado em `http://127.0.0.1:8000`.

---

## 🔧 Como Usar  

1. Acesse o navegador e abra o endereço do servidor local.  
2. Navegue pelas páginas para **criar**, **visualizar**, **editar** e **excluir** registros.  
3. Utilize a interface para testar as operações CRUD.  

---

## 🎯 Melhorias Futuras  

- Adicionar validações avançadas no formulário.  
- Melhorar a interface utilizando frameworks como **Bootstrap**. 
- Paginação e busca de registros.  

---

## 🤝 Contribuições  

Contribuições são bem-vindas! Siga os passos abaixo para colaborar:  

1. Faça um fork do projeto.  
2. Crie uma branch para suas alterações:  
   ```bash
   git checkout -b minha-feature
   ```  
3. Faça commit das suas alterações:  
   ```bash
   git commit -m "Descrição da minha feature"
   ```  
4. Envie para o repositório remoto:  
   ```bash
   git push origin minha-feature
   ```  
5. Abra um Pull Request.  

---
