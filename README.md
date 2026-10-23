# Sistema de Gerenciamento de Oficina Mecânica

## 📋 Sobre o projeto

Este projeto consiste no desenvolvimento de um sistema web para o gerenciamento de uma oficina mecânica, com o objetivo de facilitar a organização dos clientes, veículos e agendamentos de serviços.

O sistema busca substituir os controles manuais por uma solução informatizada, tornando o gerenciamento das informações mais organizado, prático e seguro.

## 🎯 Objetivo

Desenvolver um sistema que permita cadastrar e gerenciar clientes, veículos e agendamentos de serviços, além de controlar o acesso dos usuários por meio de autenticação.

## ⚙️ Funcionalidades

### 🔐 Login
- Autenticação de usuários.
- Validação de falhas durante o login.
- Controle de acesso ao sistema.
- Opção para sair da aplicação.

### 👥 Gerenciamento de clientes
- Cadastro e consulta de clientes.
- Busca de clientes por meio de termos de pesquisa.
- Edição de informações cadastradas.
- Armazenamento dos dados no banco de dados.
- Proteção do CPF por meio de criptografia.

### 🚗 Gerenciamento de veículos
- Cadastro de veículos.
- Associação de cada veículo a um cliente previamente cadastrado.
- Consulta e gerenciamento dos veículos registrados.

### 📅 Gerenciamento de agendamentos
- Listagem dos serviços agendados.
- Organização dos agendamentos por data.
- Exibição dos dados relacionados ao cliente e ao veículo.
- Atualização da data de um agendamento existente.

### 🏠 Página principal
- Exibição do usuário autenticado.
- Acesso às funcionalidades disponíveis.
- Opção de encerramento da sessão.

## 🛠️ Tecnologias utilizadas

- **HTML5:** estruturação das páginas do sistema.
- **JavaScript:** implementação das interações e comunicação com a API.
- **API:** comunicação entre a interface e o servidor.
- **Banco de dados SQL:** armazenamento e gerenciamento das informações.

## 🔒 Segurança

O sistema considera medidas de segurança para proteger as informações dos usuários e clientes, incluindo autenticação, validação de acesso e proteção do CPF armazenado no banco de dados.

A aplicação também considera os princípios da Lei Geral de Proteção de Dados (LGPD).

## 🗄️ Banco de dados

O banco de dados é responsável por armazenar as informações dos usuários, clientes, veículos e agendamentos.

Os relacionamentos entre as entidades permitem associar os veículos aos seus respectivos clientes e relacionar os agendamentos aos serviços correspondentes.

## ▶️ Como executar o projeto

1. Faça o download ou clone o repositório do projeto.
2. Configure o ambiente necessário para executar a aplicação.
3. Crie e configure o banco de dados utilizando o script SQL do projeto.
4. Inicie o servidor responsável pela aplicação e pela API.
5. Acesse o sistema pelo navegador, conforme o endereço configurado no ambiente.

**Observação:** os comandos específicos de instalação e execução dependem da configuração do servidor e do banco de dados utilizados no projeto.

## 📌 Projeto acadêmico

Projeto desenvolvido como parte de uma atividade prática do curso Técnico em Desenvolvimento de Sistemas do SENAI, com foco na criação de uma aplicação web para solucionar problemas de organização e gerenciamento de uma oficina mecânica.
