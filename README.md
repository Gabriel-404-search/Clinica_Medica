Clinica_Medica 🏥

API de uma clínica médica desenvolvida com Java e Spring Boot, focada em boas práticas de desenvolvimento, como segurança com JWT, testes unitários, validações e arquitetura organizada. O objetivo principal foi praticar regras de negócio reais, documentar a API e empacotar a aplicação para produção.

🔧 Tecnologias utilizadas

Java 17

Spring Boot

Spring Security (JWT)

JUnit

Docker

Maven

Swagger

✅ Funcionalidades

Cadastro e gerenciamento de pacientes e médicos

Agendamento e cancelamento de consultas

Camada de segurança com autenticação JWT

Validações específicas, incluindo CPF

Documentação da API com Swagger

Empacotamento final com JAR

🔐 Segurança

Implementação de login e autenticação com tokens JWT

Filtros de autenticação e autorização

🧪 Testes

Testes unitários nos serviços e validações principais

📆 Como executar

# Build do projeto
mvn clean install

# Executar o JAR
target/clinica-medica.jar

📂 Estrutura de pacotes

src/
├── controller
├── dto
├── entity
├── repository
├── service
├── config
├── security
└── exception

👨‍💻 Autor

Gabriel Marques da Silva

