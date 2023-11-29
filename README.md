# Cardápio Virtual - README

## Descrição

Bem-vindo ao Cardápio Virtual, um sistema completo para gerenciamento de cardápios de restaurantes. Este projeto utiliza React no frontend para uma interface amigável e Java no backend para fornecer funcionalidades robustas. O banco de dados PostgreSQL é empregado para armazenar e gerenciar os dados relacionados aos itens do cardápio.

## Requisitos do Sistema

Certifique-se de ter as seguintes ferramentas instaladas em sua máquina antes de executar o programa:

- Node.js
- npm (Node Package Manager)
- Java SDK
- PostgreSQL

## Configuração do Banco de Dados

1. Crie um banco de dados PostgreSQL com o nome desejado.
2. Atualize as informações de conexão do banco de dados no arquivo `application.properties` no diretório `backend/src/main/resources`.

## Configuração do Backend

1. Navegue até o diretório `backend` no terminal.
2. Execute `./mvnw spring-boot:run` para iniciar o servidor backend.

## Configuração do Frontend

1. Navegue até o diretório `frontend` no terminal.
2. Execute `npm install` para instalar as dependências.
3. Atualize a URL de conexão com o backend no arquivo `src/services/api.js`.
4. Execute `npm start` para iniciar o servidor frontend.

## Uso

Acesse o sistema pelo navegador usando o endereço fornecido pelo servidor frontend. O sistema permite visualizar, adicionar, editar e excluir itens do cardápio de maneira intuitiva.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) e enviar pull requests.

## Autor

Este projeto foi desenvolvido por [Eli Soares] - https://www.linkedin.com/in/elisandro-soares/.

---

