## Refinando um Projeto Conceitual de Banco de Dados E-COMMERCE
Refinando um Projeto Conceitual de Banco de Dados E-COMMERCE, atravez do MySQL Workbench

Contexto: Levantamento de requisitos
<br> Projeto Conceitual: Modelo Entidade Relacionamento
<br>Projeto Lógico: Modelo Relacional


<br>Modelando E-COMMERCE:
<br>Entidades: 
<br>Cliente; 
<br>Pedido; 
<br>Produto; 
<br>Fornecedor & estoque.

Produto:
Os produtos são vendidos por uma unica plataforma online. Porém, deve haver vendedores distintos
Sendo assim, cada produto possui um fornecedor
Um ou mais produtos podem compor o pedido

Cliente:
O cliente pode se cadastrar no site com seu CPF ou CNPJ;
O valor do frete será ajustado de acordo com o endereço do cliente;
Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto

Pedido:
Os pedidos são produtos solicitados pelos clientes, possuindo informações de compra, endereço e status da entrega;
O pedido pode ser cancelado por opção do cliente;

Observações a seguir:
<br>Cliente PJ e PF - Uma conta pode ser PJ ou PF, mas não pode ter as duas informações
<br>Pagamento - A forma de pagamento pode ser mais de um cadastro;
<br>Entrega - possui status e código de restreio
