# 💰 Sistema de Gestão de Orçamentos com Bubble e IA

## 📝 Descrição do Projeto

Este projeto consiste no desenvolvimento de uma aplicação web para gerenciamento de orçamentos utilizando a plataforma Bubble com apoio de Inteligência Artificial.

O objetivo principal foi desenvolver um sistema capaz de organizar clientes, controlar orçamentos e gerenciar informações de forma estruturada e segura, aplicando conceitos fundamentais de engenharia de software.

A Inteligência Artificial foi utilizada como ferramenta de apoio para acelerar o desenvolvimento inicial da aplicação. Após a geração inicial, foram realizados ajustes manuais para garantir melhor funcionamento, segurança e organização do sistema.

---

## 🚀 Tecnologias Utilizadas

### Plataforma
- Bubble (No-Code)

### Ferramentas
- Inteligência Artificial
- Modelagem de Dados
- Workflows
- Option Sets

### Conceitos Aplicados
- Engenharia de Software
- Arquitetura de Sistemas
- Banco de Dados Relacional
- Segurança da Informação
- Privacy by Design

---

## 🏗 Estrutura do Sistema

A aplicação foi construída utilizando uma arquitetura baseada em usuários autenticados.

### Relacionamentos

- Um usuário pode possuir vários clientes
- Um cliente pode possuir vários orçamentos
- Cada orçamento pertence a um único cliente
- Cada orçamento pertence ao usuário criador

Essa estrutura permite melhor organização e isolamento dos dados.

---

## 📊 Modelagem de Dados

### Usuário (User)

Campos:

- Nome
- Email

### Cliente

Campos:

- Nome
- Telefone
- Email
- Criado_por

### Orçamento

Campos:

- Título
- Valor
- Cliente
- Status
- Criado_por

### Status do orçamento

- Pendente
- Aprovado
- Rejeitado

---

## 🔒 Segurança e Privacidade

Foram implementadas regras de privacidade utilizando o conceito de Privacy by Design.

Aplicações realizadas:

✔ Restrição de acesso por usuário

✔ Isolamento de informações

✔ Remoção de permissões públicas

✔ Testes realizados em ambiente anônimo

---

## 📚 Resultados e Aprendizados

Durante o desenvolvimento deste projeto foi possível aplicar conhecimentos relacionados a:

- Modelagem de dados
- Estruturação de workflows
- Relacionamentos entre entidades
- Segurança da informação
- Organização de sistemas
- Utilização de IA no desenvolvimento

O projeto demonstrou a importância da validação humana para garantir qualidade e confiabilidade nas aplicações.

---

## 🔧 Melhorias Futuras

Possíveis evoluções do projeto:

- Integração com APIs
- Migração para React e Node.js
- Implementação de relatórios
- Dashboard com métricas

---

[Voltar ao início](../README.md)
