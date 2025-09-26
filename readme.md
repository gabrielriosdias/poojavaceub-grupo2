🎵Loja de Música – Projeto em Java

DESCRIÇÃO

Este projeto simula o funcionamento de uma loja de instrumentos musicais, utilizando Java e UML (Mermaid).
Foram aplicados conceitos de herança, composição, enum e associações para modelar as entidades do sistema.

O trabalho foi dividido em duas etapas:

Modelagem UML (classes Usuario, Cliente e Funcionario, entre outras).

Implementação em Java (produtos, vendas e lógica do sistema).

📂 ESTRUTURA DO PROJETO
/loja-musica
├── src/
│   ├── Produto.java
│   ├── Instrumento.java
│   ├── Acessorio.java
│   ├── ItemVenda.java
│   ├── Venda.java
│   ├── Funcionario.java
│   ├── Categoria.java
│   └── Main.java
├── Usuario.md
├── Produto.md
├── Venda.md
├── Pedido.md
├── Fornecedor.md
└── README.md
▶️ COMO EXECUTAR
1. Compilar
javac src/*.java

2. Executar
java -cp src Main

✅ CONCLUSÃO

Foi aplicada herança (Produto → Instrumento e Acessorio).

Utilizado enum (Categoria).

Implementada composição (Venda possui ItemVenda).

Criado um fluxo completo: cadastro de produtos → geração de venda → cálculo do total.
