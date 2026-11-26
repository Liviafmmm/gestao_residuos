# Sistema de Gestão de Resíduos Sólidos – Prefeitura de Amparo

## Descrição

Este projeto foi desenvolvido durante as aulas do curso de Desenvolvimento de Sistemas do SENAI. Consiste em uma API back-end criada com Node.js, utilizando a arquitetura MVC e o banco de dados MariaDB.

O sistema permite registrar e acompanhar pontos de descarte irregular de resíduos na cidade de Amparo, como lixo, entulho e materiais eletrônicos. Também possui funcionalidades para cadastrar, consultar e atualizar usuários e ocorrências, além de realizar login.

## Diagramas

Os diagramas representam a estrutura do banco de dados e o relacionamento entre as tabelas do sistema.

![Diagrama DER](imagens/diagrama/der_residuos.png)

![Diagrama MER](imagens/diagrama/mer_der_residuos.png)

## Tecnologias utilizadas

- Node.js
- Express
- MariaDB / MySQL
- XAMPP
- CORS
- Thunder Client / Postman / Insomnia

## Como executar o projeto

### 1. Pré-requisitos

- Node.js instalado.
- XAMPP instalado.
- Serviço MySQL iniciado pelo painel do XAMPP.

### 2. Configurar o banco de dados

Abra o MySQL Workbench ou outra ferramenta de gerenciamento e execute o arquivo `script.sql`, localizado na pasta `db`.

### 3. Instalar as dependências

Abra o terminal na pasta principal do projeto e execute:

```bash
npm install
```

### 4. Iniciar o servidor

Execute o comando:

```bash
npm run dev
```

O servidor estará disponível em:

`http://localhost:3000`

## Testes da API

Os testes foram realizados utilizando o Thunder Client para verificar o funcionamento das rotas.

### Testes de usuários

**Teste da rota inicial**

![Teste da rota inicial](imagens/prints/ocorrencias/testar_rotas.png)

**Cadastro de usuário**

![Cadastro de usuário](imagens/prints/ocorrencias/cadastrar_usuario.png)

**Listagem de usuários**

![Listagem de usuários](imagens/prints/ocorrencias/listar_usuario.png)

**Atualização de usuário**

![Atualização de usuário](imagens/prints/ocorrencias/atualizar_usuario.png)

**Teste de login**

![Teste de login](imagens/prints/ocorrencias/testar_login.png)

### Testes de ocorrências

**Cadastro de ocorrência**

![Cadastro de ocorrência](imagens/prints/usuario/cadastrar_ocorrencia.png)

**Listagem de ocorrências**

![Listagem de ocorrências](imagens/prints/usuario/listar_ocorrencia.png)

**Atualização de ocorrência**

![Atualização de ocorrência](imagens/prints/usuario/atualizar_ocorrencia.png)

**Resumo de ocorrências tratadas**

![Resumo de ocorrências](imagens/prints/usuario/resumir_ocorrencia.png)