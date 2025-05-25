# 📘 Documentação Swagger - API 3º Semestre

Este repositório contém a documentação dos endpoints da API desenvolvida pela equipe SQLutions no 3º semestre.

## 🔗 Acesso à Documentação

Após executar o backend, acesse:

**[http://localhost:8080/api/swagger-ui/index.html](http://localhost:8080/api/swagger-ui/index.html)**

---

## 🚀 Como rodar a aplicação

Para que a documentação do Swagger funcione corretamente, é necessário subir o backend. Abaixo estão os passos principais, mas recomendamos verificar os repositórios principais para instruções completas:

### 🔧 Backend

Repositório: [API-3-Semestre-Backend](https://github.com/SQLutions-FATEC/API-3-Semestre-Backend)

#### Requisitos:

- IntelliJ IDEA
- Docker
- Java 21 (preferencialmente Azul Zulu Community)
- Git

#### Passos rápidos:

```bash
git clone https://github.com/SQLutions-FATEC/API-3-Semestre-Backend.git
cd API-3-Semestre-Backend
```

- Configure o Java 21 no IntelliJ (Project Structure > SDK)
- Execute o Docker com o comando:

```bash
docker compose up -d
```

- Rode a aplicação pelo IntelliJ.
- Acesse a documentação Swagger na [porta 8080](http://localhost:8080/api/swagger-ui/index.html)

### 🌐 Frontend

Repositório: [API-3-Semestre-Frontend](https://github.com/SQLutions-FATEC/API-3-Semestre-Frontend)

Você pode executar o frontend em paralelo com o backend, especialmente para visualizar o consumo dos endpoints documentados.

#### Passos rápidos:

```bash
git clone https://github.com/SQLutions-FATEC/API-3-Semestre-Frontend.git
cd API-3-Semestre-Frontend
npm install
npm run dev
```

---

## 📚 Sobre o Swagger

A documentação Swagger é baseada em anotações no código-fonte da API Java com Spring Boot. Ela permite:

- Visualizar todos os endpoints disponíveis
- Ver os métodos HTTP, parâmetros e respostas esperadas
- Testar os endpoints diretamente na interface