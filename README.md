# 🚀 TaskFlow

Sistema de gerenciamento de tarefas desenvolvido como projeto da disciplina, com foco na aplicação de conceitos de **DevOps**, integração de serviços e conteinerização.

---

## 📌 Objetivo

O TaskFlow tem como objetivo permitir o controle e organização de tarefas de forma simples, possibilitando:

* Cadastro de tarefas
* Acompanhamento de status
* Organização de atividades

Além disso, o projeto visa aplicar boas práticas de desenvolvimento com:

* Separação de responsabilidades (front-end, back-end, banco)
* Uso de containers com Docker
* Controle de versão com GitFlow

---

## 🛠️ Tecnologias Utilizadas

### 🔹 Front-end

* React

### 🔹 Back-end

* Java 17
* Spring Boot

### 🔹 Banco de Dados

* PostgreSQL

### 🔹 DevOps

* Docker
* Docker Compose
* GitHub
* GitFlow

---

## 📁 Estrutura do Projeto

```
taskflow/
├── frontend/        # Interface do usuário (React)
├── backend/         # API (Spring Boot)
├── database/        # Scripts SQL (init.sql)
├── docker-compose.yml
├── README.md
└── .gitignore
```

---

## ⚙️ Como Executar o Projeto

### 📋 Pré-requisitos

* Docker instalado
* Docker Compose instalado

---

### ▶️ Passo a passo

1. Clone o repositório:

```
git clone https://github.com/CarlosFelipeV/taskflow.git
```

2. Acesse a pasta do projeto:

```
cd taskflow
```

3. Execute o comando:

```
docker-compose up --build
```

---

## 🌐 Acessos

* Front-end: http://localhost:3000
* Back-end: http://localhost:8080

---

## 🐳 Containers

O sistema é composto pelos seguintes serviços:

* **frontend** → Interface React
* **backend** → API Spring Boot
* **db** → Banco PostgreSQL

---

## 🔄 GitFlow

O projeto segue o modelo GitFlow:

* `main` → versão estável (entrega)
* `develop` → integração das funcionalidades
* `feature/*` → desenvolvimento de novas funcionalidades

---

## 📌 Status do Projeto

🚧 Em desenvolvimento
✔️ Estrutura inicial concluída
✔️ Ambiente conteinerizado funcional

---

## 👨‍💻 Autor

* Carlos Felipe
* Projeto acadêmico

---
