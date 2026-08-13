# 🐾 AU FOOD

## Sistema de gerenciamento para loja de produtos para pets

Projeto desenvolvido utilizando **ServiceNow App Engine Studio**, com o objetivo de aplicar na prática conceitos de desenvolvimento de aplicações, estruturação de dados, relacionamentos entre tabelas, controle de acesso e automação de processos.

## 📌 Sobre o projeto

A **AU FOOD** é uma aplicação desenvolvida para auxiliar no gerenciamento de uma loja fictícia de produtos para pets.

O sistema permite organizar informações relacionadas a **produtos, estoque e pedidos**, utilizando tabelas relacionadas e recursos da plataforma ServiceNow.

O projeto foi desenvolvido durante minha formação em ServiceNow App Engine Studio, permitindo aplicar na prática os conhecimentos adquiridos ao longo dos estudos.

## ⚙️ Funcionalidades

- Cadastro e gerenciamento de produtos;
- Controle de estoque;
- Registro e gerenciamento de pedidos;
- Importação de dados a partir de arquivos Excel;
- Criação e configuração de tabelas e campos;
- Relacionamentos e referências entre tabelas;
- Utilização de registros de empresas e marcas existentes na plataforma;
- Identificação automática dos produtos;
- Controle de produtos ativos e inativos;
- Classificação de produtos por status;
- Inclusão de imagens nos registros dos produtos;
- Personalização de listas e formulários.

## 🗂️ Estrutura de dados

A aplicação possui três tabelas principais:

- **Produto**
- **Estoque**
- **Pedido**

Foram utilizados campos de referência para permitir o relacionamento entre informações das diferentes tabelas e também o aproveitamento de registros já existentes na plataforma ServiceNow.

## 🏷️ Categorias e subcategorias

A aplicação utiliza campos dependentes para organizar os produtos.

Exemplos:

**Alimentos**
- Alimentos para cachorro
- Alimentos para gato

**Brinquedos**
- Bolinhas
- Bambolês
- Pelúcia

**Acessórios**
- Higiene
- Roupas

Dessa forma, as opções disponíveis em **Subcategoria** são apresentadas de acordo com a **Categoria** selecionada.

## 🔐 Controle de acesso

Foram configuradas diferentes funções de usuário com permissões específicas dentro da aplicação:

- **Vendedor (sales)**
- **Usuário (user)**
- **Administrador (admin)**
- **Gestor (manager)**

Cada função possui permissões específicas para operações como **criação, leitura, alteração e exclusão de registros**, de acordo com sua responsabilidade dentro da aplicação.

## 🔄 Automação de processos

Foi desenvolvido um **Flow** denominado `Novo Pedido` para aplicar conceitos de automação de processos utilizando os recursos da plataforma ServiceNow.

O desenvolvimento permitiu trabalhar com conceitos de execução automática de ações a partir de eventos ocorridos dentro da aplicação.

## 🛠️ Tecnologias e recursos utilizados

- ServiceNow
- App Engine Studio
- Flow
- Tabelas e formulários
- Campos de referência
- Relacionamentos entre dados
- Controle de acesso por funções
- Importação de dados via Excel
- Personalização de listas e formulários

## 📸 Demonstração

Nesta seção serão apresentadas imagens das principais funcionalidades e configurações desenvolvidas na aplicação AU FOOD.

## 🎯 Aprendizados

O desenvolvimento da AU FOOD permitiu aplicar na prática conhecimentos relacionados a:

- Estruturação de aplicações;
- Modelagem e organização de dados;
- Relacionamentos entre tabelas;
- Configuração de permissões;
- Automação de processos;
- Organização de interfaces;
- Desenvolvimento de soluções utilizando ServiceNow App Engine Studio.

---

**Projeto desenvolvido por Arthur Peres França Souza**  
Estudante de Engenharia de Software
