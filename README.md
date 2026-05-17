# 💰 Sistema de Gestão de Orçamentos com Bubble e IA

## 📝 Descrição do Projeto

Este projeto consiste no desenvolvimento de uma aplicação web para gerenciamento de orçamentos utilizando a plataforma Bubble com apoio de Inteligência Artificial.

O objetivo principal foi desenvolver um sistema capaz de organizar clientes, controlar orçamentos e gerenciar informações de forma estruturada e segura, aplicando conceitos fundamentais de engenharia de software.

Embora a IA tenha sido utilizada para acelerar o desenvolvimento inicial da aplicação, toda a estrutura lógica, regras de negócio, workflows e mecanismos de segurança foram revisados e ajustados manualmente, demonstrando a importância do desenvolvedor no processo de validação e melhoria do sistema.

---

## 🚀 Tecnologias Utilizadas

**Plataforma**
- Bubble (No-Code)

**Ferramentas**
- Inteligência Artificial aplicada ao desenvolvimento
- Modelagem de Dados
- Workflows
- Option Sets

**Conceitos Aplicados**
- Engenharia de Software
- Arquitetura de Sistemas
- Segurança da Informação
- Privacy by Design
- Banco de Dados Relacional

---

## 🏗 Estrutura do Sistema

A aplicação foi construída utilizando uma arquitetura baseada em usuários autenticados:

### Relacionamentos:

- Um usuário pode possuir vários clientes
- Um cliente pode possuir vários orçamentos
- Cada orçamento pertence a um único cliente
- Cada orçamento pertence ao usuário criador

Essa estrutura garante isolamento de dados entre usuários e evita acessos indevidos.

---

## 📊 Modelagem de Dados

### Usuário (User)

Campos:

- Nome
- E-mail

### Cliente

Campos:

- Nome
- Telefone
- E-mail
- Criado_por

### Orçamento

Campos:

- Título
- Valor
- Cliente
- Status
- Criado_por

### Status do Orçamento (Option Set)

- Pendente
- Aprovado
- Rejeitado

---

## 🔒 Segurança e Privacidade

Foram implementadas regras de privacidade seguindo o princípio de **Privacy by Design**.

Medidas aplicadas:

✔ Restrição de acesso por usuário

✔ Remoção de permissões públicas

✔ Isolamento de dados

✔ Testes realizados em navegação anônima

---

## 📚 Resultados e Aprendizados

Durante o desenvolvimento deste projeto foi possível aplicar conhecimentos relacionados a:

- Modelagem de dados
- Estruturação de workflows
- Segurança da informação
- Relacionamentos entre entidades
- Organização de sistemas
- Uso da Inteligência Artificial como apoio ao desenvolvimento

Além do aprendizado técnico, o projeto demonstrou a importância da revisão humana para garantir qualidade, segurança e funcionamento adequado das aplicações.

---

## 🔧 Possibilidades Futuras

Como evolução do projeto, o sistema poderá ser migrado para tecnologias tradicionais como:

- React
- Node.js
- APIs REST
- Banco de dados SQL

---

[Voltar ao início](../README.md)
