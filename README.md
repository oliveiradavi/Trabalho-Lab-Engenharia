# Trabalho-Lab-Engenharia


Sistema CRUD de Produtos
Autor: Davi Almeida de Oliveira

# Instalação local
Para utilizar o sistema em ambiente local é necessário:

1- Java EE
2- JDK 8
3- JRE 1.8
4- Servidor compatível com aplicações Java

Importe o projeto no eclipse e utilize um servidor para rodar em sua máquina.
Servidor recomendado: Tomcat 7.0.78

# Sistema

Ao abrir o sistema, nos deparamos com a página inicial.
No menu no canto superior esquerdo podemos clicar em Cadastros -> Produtos, ou em Sobre.

Ao clicar em Produtos temos uma tela na qual são exibidos todos os produtos cadastrados no banco de dados, separados por páginas.
É possível organizar os produtos por Código, Nome, Descrição ou Preço.
É possível filtrar produtos por Código, Nome, Descrição ou Preço.
É possível excluir produtos clicando no botão excluir, localizado à direita do campo Preço.
É possível Editar um produto clicando no botão editar, localizado à direita do botão excluir.

No campo inferior da tela temos um botão Adicionar Produto.
Para adicionar um produto é necessário entrar com um nome do produto (texto), uma descrição do produto(texto) e um preço do produto (double).

Ao adicionar ou remover um produto, uma mensagem deve ser exibida no campo superior direito da aplicação, informando o usuário do ocorrido.
