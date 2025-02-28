# Spring Boot Hello World

## Descrição
Este projeto é uma aplicação simples desenvolvida com **Spring Boot**, que implementa um endpoint REST retornando a mensagem **"Hello, World!"**. 

## Tecnologias Utilizadas
- **Java 23**
- **Spring Boot** (Spring Web)
- **Maven**

## Estrutura do Projeto
A estrutura do projeto segue a seguinte organização:
```
SpringBootHelloWorld/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com/
│   │   │   │   ├── atividade/
│   │   │   │   │   ├── controller/
│   │   │   │   │   │   ├── ControllerApplication.java
│   │   │   │   │   │   ├── HelloController.java
│   │   ├── resources/
│   │   │   ├── application.properties
├── pom.xml
└── README.md
```

## ▶ Como Executar a Aplicação

### 1️⃣ Clonar o Repositório
```sh
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 2️⃣ Compilar e Rodar
#### Via Maven:
```sh
mvn spring-boot:run
```

#### Ou via Java diretamente:
```sh
mvn clean package
java -jar target/*.jar
```

### 3️⃣ Testar o Endpoint
Após iniciar a aplicação, acesse no navegador ou via Postman:
```
http://localhost:8080/test
```
**Resposta esperada:**
```
Hello, World!
```
