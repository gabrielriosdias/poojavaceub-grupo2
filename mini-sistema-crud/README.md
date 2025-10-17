#  Mini Sistema CRUD em Java (ArrayList)

##  Objetivo
Este projeto tem como objetivo implementar um **mini sistema de cadastro em memória**, com operações **CRUD completas** para Funcionário, Produto e Cliente.  
O sistema é totalmente executado via **console**, utilizando **ArrayList** como repositório em memória, sem banco de dados ou arquivos.

---

##  Tecnologias Utilizadas
- **Java 17+**
- **ArrayList** (armazenamento em memória)
- **Scanner** (entrada de dados)
- **Programação orientada a objetos**
- Nenhum framework ou banco de dados (simples e didático)

---

##  Estrutura de Pastas

mini-sistema-crud/
├── src/
│ ├── model/
│ │ ├── Funcionario.java
│ │ ├── Produto.java
│ │ └── Cliente.java
│ │
│ ├── repository/
│ │ ├── FuncionarioRepositoryMemoria.java
│ │ ├── ProdutoRepositoryMemoria.java
│ │ └── ClienteRepositoryMemoria.java
│ │
│ ├── view/
│ │ ├── MenuFuncionario.java
│ │ ├── MenuProduto.java
│ │ ├── MenuCliente.java
│ │ └── MenuPrincipal.java
│ │
│ └── Main.java
│
└── README.md

yaml
Copiar código

---

##  Como Executar o Projeto

###  1. Compilar o código
No terminal (na pasta raiz do projeto):

```bash
javac src/**/*.java
Se o terminal não reconhecer o **, use:

bash
Copiar código
javac src/model/*.java src/repository/*.java src/view/*.java src/Main.java
 2. Executar o sistema
bash
Copiar código
java -cp src Main
O menu principal será exibido no console.

 Navegação dos Menus
 Menu Principal
java
Copiar código
1) Gerenciar Funcionários
2) Gerenciar Produtos
3) Gerenciar Clientes
4) Cadastrar Cliente (atalho)
5) Cadastrar Produto (atalho)
0) Sair
 Submenu (para cada entidade)
Copiar código
1) Cadastrar
2) Listar
3) Buscar por ID
4) Atualizar por ID
5) Excluir por ID
0) Voltar
 Campos das Entidades
 Funcionário
Campo	Tipo	Descrição
id	int	Gerado automaticamente
nome	String	Nome do funcionário
salario	double	Salário
matricula	String	Código de matrícula

 Produto
Campo	Tipo	Descrição
id	int	Gerado automaticamente
nome	String	Nome do produto
preco	double	Preço
quantidadeEmEstoque	int	Quantidade disponível

 Cliente
Campo	Tipo	Descrição
id	int	Gerado automaticamente
nome	String	Nome do cliente
telefone	String	Telefone de contato
email	String	Endereço de e-mail

 Testes Realizados
Para validar o funcionamento completo do sistema, foram realizados os seguintes testes:

 Funcionário
Cadastrar dois funcionários

Atualizar o salário de um funcionário

Excluir um funcionário

Listar para confirmar as alterações

 Produto
Cadastrar dois produtos

Atualizar o preço de um produto

Excluir um produto

Listar para confirmar as alterações

👤 Cliente
Cadastrar dois clientes

Atualizar o telefone de um cliente

Excluir um cliente

Listar para confirmar as alterações

 Todas as operações funcionaram corretamente e as listas refletiram as mudanças esperadas.

 Observações
Todos os dados são armazenados apenas em memória (ArrayList).

Ao encerrar o programa, os dados são perdidos.

O código foi desenvolvido de forma modular, com pacotes separados para model, repository e view.

Não utiliza Streams, Optional, banco de dados ou frameworks — tudo feito com lógica básica e estruturas simples.

 Comandos Git (para publicar no GitHub)
1. Inicializar o repositório
bash
Copiar código
git init
git add .
git commit -m "Mini sistema CRUD completo em Java"

2. Criar repositório no GitHub
Acesse https://github.com/new
Crie o repositório com o nome: mini-sistema-crud-java
Não adicione README nem .gitignore

3. Conectar e enviar
bash
git remote add origin https://github.com/seuusuario/mini-sistema-crud-java.git
git branch -M main
git push -u origin main

✨ Autor
Camilla Valenzuela
Estudante de Engenharia de Software — UniCEUB
Desenvolvido para atividade prática de programação em Java.






