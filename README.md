# Sistema de Consulta de Livros 📚

## Descrição

Este projeto foi desenvolvido em **Java** com o objetivo de consumir uma **API de livros** e permitir a interação do usuário por meio de um menu no terminal.

O sistema permite buscar livros pelo título, registrar as informações e realizar consultas sobre livros e autores armazenados no sistema.

A aplicação utiliza a API **Gutendex**, que disponibiliza informações sobre livros do domínio público.

---

## Funcionalidades

O sistema possui cinco opções principais de interação com o usuário:

1. **Buscar livro pelo título**

   * Realiza uma consulta na API de livros.
   * O livro encontrado é registrado no sistema.

2. **Listar livros registrados**

   * Exibe todos os livros que foram adicionados.

3. **Listar autores**

   * Mostra os autores cadastrados e seus respectivos livros.

4. **Listar autores em determinado ano**

   * Retorna os autores que estavam vivos no ano informado pelo usuário.

5. **Listar livros em determinado idioma**

   * Permite consultar livros cadastrados de acordo com o idioma.

---

## Tecnologias Utilizadas

* Java
* Consumo de API REST
* API Gutendex
* Programação Orientada a Objetos
* Estrutura de dados (List)

---

## Estrutura do Projeto

O projeto foi desenvolvido em um único arquivo Java:

SistemaLivros.java

Esse arquivo contém:

* Classe principal do programa
* Classe Autor
* Classe Livro
* Menu interativo
* Consumo da API
* Métodos de busca e listagem

---

## Como Executar o Projeto

1. Baixar ou clonar o projeto.
2. Abrir o projeto em uma IDE Java (IntelliJ, Eclipse ou NetBeans).
3. Compilar o arquivo:

```
javac SistemaLivros.java
```

4. Executar o programa:

```
java SistemaLivros
```

5. Escolher uma das opções do menu para interagir com o sistema.

---

## API Utilizada

O sistema consome dados da seguinte API pública:

https://gutendex.com/

Essa API fornece informações como:

* título do livro
* autor
* idioma
* número de downloads

---

## Objetivo do Projeto

O objetivo deste projeto é praticar:

* Consumo de APIs em Java
* Manipulação de dados
* Programação orientada a objetos
* Interação com o usuário via terminal

---
