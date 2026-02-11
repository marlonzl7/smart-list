# Smart List

Já foi ao mercado e esqueceu de fazer a lista de compras?
Ou até fez a lista, mas acabou esquecendo algum item importante?

O **Smart List** é um projeto que resolve exatamente esse problema.
Ele automatiza a criação da lista de compras com base no consumo diário dos itens, ajudando famílias a manterem o controle de estoque e evitando compras desnecessárias ou esquecimentos.

## O que é o Smart List?

O Smart List é uma aplicação dividida em backend e frontend que permite:
- Gerenciar um inventário doméstico
- Registrar o consumo diário de itens
- Criar categorias de itens
- Gerar automaticamente listas de compras
- Atualizar o estoque após a compra

## Como funciona?

O sistema é composto por dois projetos principais:

- **Smart List API**: responsável pelas regras de negócio, autenticação, persistência de dados e geração automática da lista de compras.
- **Smart List Web**: interface web que consome a API e permite ao usuário interagir com o sistema.

## Arquitetura

O Smart List segue uma arquitetura baseada em API REST:

Usuário → Smart List Web → Smart List API → Banco de Dados

## Repositórios

- Backend (API): https://github.com/marlonzl7/smart-list-api
- Frontend (Web): https://github.com/marlonzl7/smart-list-web
