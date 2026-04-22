# Dio Bank

Projeto original desenvolvido por [Nathally Souza](https://github.com/nathyts), refatorado e finalizado como parte do desafio proposto no curso de TypeScript.

## Sobre o projeto

API simples em TypeScript para gerenciamento de usuários, com foco em boas práticas de organização de código, validações e testes unitários utilizando Jest.

## Tecnologias

- TypeScript
- Node.js
- Express
- Jest

## O que foi implementado

- Função de deletar usuário no `service` e no `controller`
- Refatoração das rotas (`routes`)
- Funcionalidade `getAllUsers`
- Validação dos campos `name` e `email` na criação de usuário
- Testes unitários cobrindo:
  - criação de usuário
  - retorno de todos os usuários
  - deleção de usuário
  - validação de `name` obrigatório
  - validação de `email` obrigatório

## Status do desafio

- [x] Testes unitários pendentes no controller
  - [x] Erro quando o `name` não é informado
  - [x] Verificação da função `getAllUsers`
- [x] Validação para o campo `email`
  - [x] Bloqueio da criação sem `email`
  - [x] Teste unitário correspondente
- [x] Refatorar e implementar a rota para deletar usuário
  - [x] Rota refatorada
  - [x] Testes unitários adicionados

## Pré-requisitos

- [Node.js](https://nodejs.org/)
- npm

## Como rodar o projeto

Clone o repositório:

    git clone <URL_DO_REPOSITORIO>

Acesse a pasta:

    cd <NOME_DO_PROJETO>

Instale as dependências (inclui dependências de desenvolvimento e testes):

    npm install

Execute em modo desenvolvimento:

    npm run dev

Rode os testes unitários:

    npm test

## Refatorado por

**Jean Guilherme Borges**
Dev Full Stack e Estudante de Ciência da Computação