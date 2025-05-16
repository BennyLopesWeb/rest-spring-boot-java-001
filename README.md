# 🛠️ API REST com Spring Boot - Projeto 001

Este projeto é uma **API RESTful** desenvolvida com **Spring Boot**, com o objetivo de praticar a criação de endpoints, integração com banco de dados relacional e aplicação de boas práticas em projetos Java.

---

## 🚀 Tecnologias Utilizadas

- Java 17+
- Spring Boot
- Spring Data JPA
- H2 Database (banco de dados em memória)
- Maven
- Lombok
- Postman (para testes)

---

## 🎯 Funcionalidades

- ✅ Cadastro de clientes
- ✅ Listagem de todos os clientes
- ✅ Busca por ID
- ✅ Atualização de dados
- ✅ Exclusão de clientes

---

## 📂 Estrutura do Projeto

src
├── main
│ ├── java
│ │ └── com.benny.restapi
│ │ ├── controllers
│ │ ├── domain
│ │ ├── repositories
│ │ ├── services
│ │ └── config
│ └── resources
│ ├── application.properties
│ └── data.sql



---

## ⚙️ Como Executar o Projeto

### Pré-requisitos

- Java 17+ instalado
- Maven

### Passos

1. Clone o repositório:

```bash
git clone https://github.com/BennyLopesWeb/rest-spring-boot-java-001.git

2. Acesse a pasta do projeto:
cd rest-spring-boot-java-001

3. Execute o projeto:
./mvnw spring-boot:run

A API estará disponível em: http://localhost:8080

🔎 Endpoints Exemplares
GET /clients → Lista todos os clientes

GET /clients/{id} → Retorna um cliente por ID

POST /clients → Cria um novo cliente

PUT /clients/{id} → Atualiza um cliente

DELETE /clients/{id} → Remove um cliente

🧪 Testes com Postman
Você pode usar o Postman ou Insomnia para testar os endpoints.
Caso o projeto use dados automáticos via data.sql, alguns registros já estarão disponíveis ao iniciar a aplicação.

👨‍💻 Autor
Desenvolvido por Benny Lopes

📌 Licença
Este projeto está licenciado sob a licença MIT.


