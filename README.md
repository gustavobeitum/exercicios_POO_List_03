# Gerenciador de Lista de Tarefas

## 📝 Descrição

Este projeto é um gerenciador de lista de tarefas (To-Do List) desenvolvido com o objetivo de aprimorar os conhecimentos em Programação Orientada a Objetos (POO) e praticar a criação de uma arquitetura com frontend e backend desacoplados.

## ✨ Funcionalidades

* Criação, leitura, atualização e exclusão de tarefas.
* Interface de usuário reativa construída em Angular.
* API REST robusta para gerenciar os dados das tarefas.

## 💻 Tecnologias Utilizadas

O projeto foi dividido em duas partes principais:

**Backend:**
* **Java 21**
* **Spring Boot 3.5.4**
* **Maven**

**Frontend:**
* **Angular CLI 19.2.15**
* **Node.js 23.x**
* **TypeScript**

**Ambiente de Desenvolvimento:**
* **Visual Studio Code**

## 🚀 Como Executar o Projeto

Para executar este projeto, você precisará ter o Java (JDK 21), o Node.js e o Angular CLI instalados. Siga os passos abaixo.

### 1. Clonar o Repositório

```bash
git clone [https://github.com/gustavobeitum/exercicios_POO_List_03.git](https://github.com/gustavobeitum/exercicios_POO_List_03.git)
```

### 2. Executar o Backend (Spring Boot)

Navegue até a pasta do backend.

```bash
cd todolist-api
```

Para executar, execute no terminal
```bash
./mvnw spring-boot:run
```
Depois de rodar o backend o Banco de Banco estará disponível em `http://localhost:8080/h2-console/login.jsp`.

### 3. Executar o Frontend (Angular)

Abra um **novo terminal**, navegue até a pasta do frontend, instale as dependências e inicie o servidor de desenvolvimento.

```bash
cd todolist-web

# Instalar as dependências (execute apenas na primeira vez)
npm install

# Iniciar o servidor de desenvolvimento
ng serve --open
```
A aplicação estará acessível em `http://localhost:4200`.

## 👨‍💻 Autor

Desenvolvido por **Gustavo Beitum**.

* **GitHub:** [gustavobeitum](https://github.com/gustavobeitum)
