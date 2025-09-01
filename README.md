# API para Cadastro de Usuários em Java 🚀

<p align="center">
  <img src="https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge" alt="Status do Projeto: Concluído"/>
</p>

## 📖 Sobre o Projeto

Este projeto é uma API RESTful completa para o gerenciamento de usuários, desenvolvida em **Java** com o framework **Spring Boot**. A API é responsável por toda a lógica de negócios, validação e persistência de dados em um banco de dados relacional.

O objetivo foi aplicar e consolidar conhecimentos no ecossistema Spring, incluindo a criação de controllers, services e repositories, além da utilização do **Spring Data JPA** para abstrair o acesso aos dados e **Lombok** para reduzir código boilerplate.

## 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando as seguintes tecnologias Back-End:

<p align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/JPA-6DB33F?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAC9SURBVDhPY/z//z8DJYCJgUI3YAb2c6B9/x9f/v8ZP/37B8/9fwYMP/7/h/X/m/H/n3H/P2b8/x/m////f2Z5+/8f7//9/f/v/39g+P+Pmf+fMv4/Y/z/B8z4/8/A8P9fMv8/Zvz/ZWD4/y/W//+D9f9/gPX/f2D5/y8Y/v8Lpv9/hOw/Px4w/P+Xhv9/mOz/P5kR/v+H6v9/MO3/P5kR/v8HqP7/A8T6/w/E+v8PJANgAAD//wMAv5o9s24LUEwAAAAASUVORK5CYII=" alt="JPA"/>
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white" alt="Maven"/>
</p>

## ✨ Funcionalidades Principais

- **Arquitetura em Camadas:** Projeto estruturado com separação de responsabilidades nas camadas de Controller (API), Service (regras de negócio) e Repository (acesso a dados).
- **Endpoints RESTful:** Implementação das rotas para **Salvar** (`POST /usuario`), **Buscar por Email** (`GET /usuario`), **Atualizar por ID** (`PUT /usuario`) e **Deletar por Email** (`DELETE /usuario`).
- **Abstração com Spring Data JPA:** Uso da interface `JpaRepository` para executar operações de banco de dados complexas com métodos simples e declarativos.
- **Injeção de Dependências:** Utilização do padrão de injeção de dependências do Spring para gerenciar os componentes da aplicação, como a injeção do `UsuarioService` no `UsuarioController`.
- **Redução de Boilerplate com Lombok:** Uso de anotações como `@Getter`, `@Setter` e `@Builder` para gerar automaticamente o código repetitivo nas entidades.

## 🚀 Como Executar

Para executar este projeto localmente, você precisará ter o Java e o Maven instalados.

1.  **Clone este repositório.**
2.  **Configure o Banco de Dados:** No arquivo `application.properties` (localizado em `src/main/resources`), configure a URL do seu banco de dados, usuário e senha.
3.  **Execute a Aplicação:** Utilize sua IDE ou execute o seguinte comando na raiz do projeto:
    ```bash
    mvn spring-boot:run
    ```
- O servidor será iniciado em `http://localhost:8080`.

## 👨‍💻 Autor

**David Arruda**.

### 📫 Onde me encontrar

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/david-viniciusarruda/)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:david.viniciusarruda@gmail.com)
