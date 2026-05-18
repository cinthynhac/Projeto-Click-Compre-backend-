# Sistema Integrado de Gestão de Lojas 🏪

Sistema desenvolvido em Java com foco em gerenciamento de lojas, produtos, vendas, clientes e funcionários, utilizando conceitos de Programação Orientada a Objetos (POO), arquitetura em camadas e padrão MVC.

---

## 🚀 Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de praticar:

* Programação Orientada a Objetos (POO)
* Arquitetura MVC
* Separação de responsabilidades
* Estruturação em camadas (`Model`, `Service`, `Controller`)
* Manipulação de listas e lógica de negócio em Java
* Construção de sistemas de gerenciamento via terminal

---

# 🧩 Funcionalidades

## 🏪 Gestão de Lojas

* Cadastrar loja
* Listar lojas
* Buscar loja por ID
* Excluir loja

---

## 📦 Gestão de Produtos

* Cadastrar produtos
* Listar produtos por loja
* Buscar produto por ID
* Excluir produto

---

## 👥 Gestão de Clientes

* Cadastrar clientes
* Listar clientes por loja
* Buscar cliente por CPF
* Excluir cliente

---

## 👨‍💼 Gestão de Funcionários

* Cadastrar funcionários
* Buscar funcionário por CPF
* Excluir funcionário

---

## 💰 Gestão de Vendas

* Registrar vendas
* Adicionar múltiplos produtos em uma venda
* Associar cliente e funcionário à venda
* Buscar venda por ID
* Buscar vendas de um cliente
* Listar vendas da loja
* Excluir venda

---

## 📊 Relatórios

* Relatório de vendas da loja
* Relatório de vendas por cliente
* Relatório de produtos com estoque baixo

---

# 🏗️ Estrutura do Projeto

```bash
src/
│
├── model/
│   ├── Loja.java
│   ├── Produto.java
│   ├── Cliente.java
│   ├── Funcionario.java
│   ├── Vendas.java
│   └── ItemVenda.java
│
├── service/
│   ├── LojaService.java
│   ├── ProdutoService.java
│   ├── ClienteService.java
│   ├── FuncionarioService.java
│   ├── VendasService.java
│   └── RelatoriosService.java
│
├── controller/
│   ├── LojaController.java
│   ├── ProdutoController.java
│   ├── ClienteController.java
│   ├── FuncionarioController.java
│   ├── VendasController.java
│   ├── RelatoriosController.java
│   └── AcessarServicosController.java
│
└── Main.java
```

---

# 🛠️ Tecnologias Utilizadas

* Java
* IntelliJ IDEA
* Programação Orientada a Objetos
* MVC
* Collections (`ArrayList`)
* Scanner (entrada de dados)

---

# 📚 Conceitos Aplicados

Durante o desenvolvimento foram aplicados conceitos como:

* Encapsulamento
* Abstração
* Responsabilidade única
* Separação entre regras de negócio e interface
* Organização em camadas
* Relacionamento entre objetos
* Manipulação de listas
* Estruturação de menus interativos

---

# ▶️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/seurepositorio.git
```

2. Abra o projeto na IDE de sua preferência.

3. Execute o arquivo:

```bash
Main.java
```

---

# 📌 Melhorias Futuras

* Persistência de dados com banco de dados
* Integração com Spring Boot
* Interface gráfica
* API REST
* Sistema de autenticação
* Atualização de registros
* Controle de estoque automático
* Relatórios avançados

---

# 👩‍💻 Desenvolvido por

## Cinthya Alves Silva

Estudante de Ciência da Computação e desenvolvedora em formação com foco em back-end, análise de dados e arquitetura de sistemas.

* Java
* SQL
* Python
* Estrutura de Dados
* MVC
* POO

---

# ⭐ Considerações

Este projeto foi desenvolvido como prática acadêmica e evolução técnica, com foco em consolidar fundamentos sólidos de desenvolvimento Java e arquitetura de software.
