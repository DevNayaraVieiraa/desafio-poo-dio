# ☕ Desafio: Dominando a Programação Orientada a Objetos com Java

Este repositório contém a minha resolução para o desafio de projeto da **DIO (Digital Innovation One)**. O objetivo foi colocar em prática os pilares da Orientação a Objetos (POO) simulando a estrutura de um Bootcamp.

## 🚀 O que foi desenvolvido?
Foi criado um sistema em Java que abstrai o domínio de um Bootcamp, onde é possível:
- Criar **Cursos** e **Mentorias**.
- Inscrever **Devs** (alunos) no Bootcamp.
- Calcular o progresso e o XP (experiência) obtido pelos Devs.

## 🛠️ Tecnologias e Ferramentas
- **Java JDK 11+**
- **IDE:** IntelliJ IDEA / VS Code
- **Git & GitHub**

## 🧠 Conceitos Praticados
Durante o desenvolvimento, foram aplicados os 4 pilares fundamentais da POO:

1.  **Abstração:** Representação de entidades do mundo real (Curso, Mentoria, Dev) em classes.
2.  **Encapsulamento:** Proteção dos atributos das classes usando modificadores de acesso e métodos Getters/Setters.
3.  **Herança:** Criação da classe mãe `Conteudo` para evitar repetição de código em `Curso` e `Mentoria`.
4.  **Polimorfismo:** Sobrescrita do método `calcularXp()` para comportamentos específicos em cada classe filha.

## 📂 Estrutura do Projeto
O código está organizado no pacote `br.com.dio.desafio.dominio` e contém as seguintes classes principais:
*   `Bootcamp.java`
*   `Curso.java`
*   `Mentoria.java`
*   `Dev.java`
*   `Conteudo.java` (Classe Abstrata)
*   `Main.java` (Classe Principal para execução e testes)

---
*Desafio realizado para fins educacionais no Bootcamp da DIO.*
