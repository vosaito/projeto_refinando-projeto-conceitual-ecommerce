# Projeto Conceitual - Refinando modelo E commerce

 Realização do desafio proposto pela instrutora Juliana da Digital Innovation One.  
 Foi feito a modelagem de um sistema de e-commerce para venda de produto da plataforma e de terceiros para clientes PF e PJ, prevendo estoque, pagamento e entrega do pedido.

 

### Escopo do Projeto
Narrativa - Produto
* Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros)
* Cada produto possui um fornecedor
* Um ou mais produtos podem compor um pedido

Narrativa - Cliente
* O cliente pode se cadastrar no site com seu CPF ou CNPJ
* O Endereço do cliente irá determinar o valor do frete
* Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto

Narrativa – Pedido
* O pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega
* Um produto ou mais compoem o pedido
* O pedido pode ser cancelado

Narrativa – Fornecedor & estoque
* Vamos pensar juntos ...

### Desafio proposto

Refinando
* Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações
* Pagamento – Pode ter cadastrado mais de uma forma de pagamento
* Entrega – Possui status e código de rastreio
