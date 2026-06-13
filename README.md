# Caderno Temático – Banco de Dados Relacionais e SQL

## 1. Contexto e Objetivos

Este projeto foi desenvolvido como parte do desafio da DIO utilizando o NotebookLM como ferramenta de aprendizagem ativa.

O tema escolhido foi Banco de Dados Relacionais e SQL, por ser uma das competências fundamentais para profissionais de tecnologia, desenvolvimento de software e análise de dados.

### Objetivos de estudo

* Compreender os conceitos fundamentais de bancos de dados relacionais.
* Aprender os principais comandos SQL.
* Entender a importância das chaves primárias e estrangeiras.
* Conhecer boas práticas de modelagem de dados.
* Identificar aplicações práticas de SQL no mercado de trabalho.

---

## 2. Curadoria de Fontes

As seguintes fontes foram utilizadas no NotebookLM:

### Fonte 1

Documentação PostgreSQL

https://www.postgresql.org/docs/

### Fonte 2

Documentação MySQL

https://dev.mysql.com/doc/

### Fonte 3

W3Schools SQL Tutorial

https://www.w3schools.com/sql/

### Fonte 4

Oracle Database Documentation

https://docs.oracle.com/en/database/

### Fonte 5

SQLBolt

https://sqlbolt.com/

---

## 3. Engenharia de Prompts

### Prompt 1

Explique banco de dados relacionais como se eu fosse um estudante iniciante de tecnologia.

**Resultado:** Obtenção de uma visão geral dos conceitos básicos.

---

### Prompt 2

Crie um resumo completo sobre SQL destacando SELECT, INSERT, UPDATE e DELETE.

**Resultado:** Geração de material estruturado para revisão.

---

### Prompt 3

Compare MySQL e PostgreSQL apresentando vantagens, desvantagens e cenários de uso.

**Resultado:** Compreensão das diferenças entre os SGBDs mais utilizados.

---

### Prompt 4

Crie um mapa mental textual sobre banco de dados relacionais.

**Resultado:** Organização visual dos conceitos estudados.

---

### Prompt 5

Quais conhecimentos são exigidos para uma vaga de Analista de Banco de Dados Júnior?

**Resultado:** Identificação das competências valorizadas pelo mercado.

---

## 4. Cicatrizes e Aprendizados

### Problema Encontrado

As primeiras respostas apresentaram conceitos muito superficiais.

### Ajuste Realizado

Foi necessário solicitar exemplos práticos e explicações mais detalhadas.

### Prompt Melhorado

Crie um resumo detalhado sobre SQL com exemplos reais de consultas e explicações voltadas para estudantes iniciantes.

### Aprendizado

Pequenas alterações nos prompts podem melhorar significativamente a qualidade das respostas geradas pela IA.

---

## 5. Miniguia de Estudos

### O que é um Banco de Dados Relacional?

Um banco de dados relacional organiza informações em tabelas relacionadas entre si. Cada tabela possui linhas (registros) e colunas (atributos).

### O que é SQL?

SQL (Structured Query Language) é a linguagem padrão utilizada para consultar, inserir, atualizar e remover dados em bancos de dados relacionais.

### Principais Comandos

#### SELECT

Consulta dados armazenados.

Exemplo:

SELECT * FROM clientes;

#### INSERT

Insere novos registros.

Exemplo:

INSERT INTO clientes(nome)
VALUES ('Maria');

#### UPDATE

Atualiza registros existentes.

Exemplo:

UPDATE clientes
SET nome = 'Ana'
WHERE id = 1;

#### DELETE

Remove registros.

Exemplo:

DELETE FROM clientes
WHERE id = 1;

### Chave Primária (Primary Key)

Identifica unicamente cada registro de uma tabela.

### Chave Estrangeira (Foreign Key)

Cria relacionamentos entre tabelas.

### Normalização

Processo utilizado para reduzir redundâncias e melhorar a organização dos dados.

---

## 6. Glossário

| Termo       | Definição                             |
| ----------- | ------------------------------------- |
| SQL         | Linguagem de consulta estruturada     |
| Tabela      | Estrutura que armazena dados          |
| Registro    | Linha de uma tabela                   |
| Campo       | Coluna de uma tabela                  |
| Query       | Consulta realizada ao banco           |
| Primary Key | Identificador único                   |
| Foreign Key | Relacionamento entre tabelas          |
| SGBD        | Sistema Gerenciador de Banco de Dados |

---

## 7. Prompts Reutilizáveis

Explique [tema] para um estudante iniciante.

Crie um resumo estruturado sobre [tema].

Liste os conceitos mais importantes relacionados a [tema].

Monte 10 questões de revisão sobre [tema].

Crie um mapa mental textual sobre [tema].

Compare [tecnologia A] e [tecnologia B].

Explique aplicações práticas de [tema] no mercado de trabalho.

---

## 8. Conclusão

O uso do NotebookLM demonstrou como a Inteligência Artificial pode auxiliar na organização do conhecimento, na síntese de conteúdos e na aprendizagem ativa. O estudo de Banco de Dados Relacionais e SQL permitiu consolidar conhecimentos essenciais para a formação na área de tecnologia e ampliar a compreensão sobre armazenamento e manipulação de dados.

## Evidências do Uso do NotebookLM

Durante o desenvolvimento deste projeto, utilizei o NotebookLM como ferramenta de aprendizagem ativa para aprofundar meus conhecimentos em Banco de Dados Relacionais e SQL.

### Atividades realizadas no NotebookLM

- Análise de fontes técnicas sobre SQL e bancos de dados relacionais;
- Geração de resumos automáticos;
- Comparação entre MySQL e PostgreSQL;
- Criação de perguntas para revisão do conteúdo;
- Organização dos principais conceitos em formato de glossário;
- Desenvolvimento de prompts reutilizáveis para estudos futuros.

### Aprendizados Obtidos

O NotebookLM facilitou a compreensão dos conceitos estudados, permitindo reunir diferentes fontes de conhecimento em um único ambiente e obter respostas contextualizadas para apoiar o processo de aprendizagem.
