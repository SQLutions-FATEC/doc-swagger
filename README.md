# 📚 Documentação da API - Sistema de Ponto e Geração de Relatórios

![sqlutions logo](https://github.com/user-attachments/assets/4884e8b3-b59a-45ba-ad13-13faa8d4d9b3)

Este repositório contém a **documentação da API REST** do projeto _**Sistema de Ponto e Geração de Relatórios**_, desenvolvido pela equipe **SQLutions**, do curso Banco de Dados - 3º semestre da Fatec São José dos Campos.

---

## 📌 Sobre o projeto

O sistema foi desenvolvido para atender a demanda da empresa **Altave**, que necessita acompanhar e fiscalizar o cumprimento de jornada dos funcionários terceirizados que atuam em navios durante processos de manutenção.

A API tem como objetivo possibilitar o registro de **movimentações (entrada e saída)** dos funcionários, assim como **cadastro de empresas, contratos, funções**, e permitir a **visualização, edição e exportação de dados** para relatórios gerenciais.

---

## 🔗 Acesse a documentação

> A documentação da API pode ser acessada através do Swagger:

📎 **Swagger UI:**  
[http://localhost:8080/swagger-ui/index.html](http://localhost:8080/swagger-ui/index.html)

---

## 📦 Endpoints disponíveis

Os principais recursos da API incluem:

- `/api/employees` – Cadastro, edição e listagem de funcionários
- `/api/companies` – Cadastro e gerenciamento de empresas
- `/api/roles` – Cadastro e consulta de funções
- `/api/contracts` – Gerenciamento de contratos com vigência
- `/api/clockins` – Registro de pontos (entrada e saída)
- `/api/reports` – Geração de relatórios filtrados e exportação para `.xlsx`

---

## ⚙️ Tecnologias Utilizadas

- **Java 17**
- **Spring Boot**
- **Spring Data JPA**
- **PostgreSQL**
- **Swagger (Springdoc OpenAPI 3)**

---

## ▶️ Como rodar localmente

1. Clone o projeto:
   ```bash
   git clone https://github.com/SQLutions-FATEC/API-3-Semestre.git
