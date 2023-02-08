# projeto-de-banco-de-dados-conceitual-e-commerce
Esquema conceitual para o cenário de E-commerce

Trata-se de venda de produtos.
É necessário identificar as partes envolvidas.
Uma aplicação vai utilizar as informações do banco de dados para vender produtos fornecendo dados para o e-commerce.

Necessidade dos projeto.
Produto, estoque, fornecedor, pedido, cliente.

Narrativa Produto:
São vendidos por uma única plataforma online.
Podem ter vendedores distintos.
Cada produto possui um fornecedor.
Um ou mais produtos podem compor um pedido.

Narrativa Cliente:
Pode se cadastrar no site com CPF ou CNPJ.
O endereço do cliente determina o valor do frete.
Pode comprar mais de um pedido.
Tem um período de carência para devolução do pedido.

Narrativa Pedido:
São criados por clientes e possuem informações de compra, endereço e status da entrega
Um produto ou mais compoem o pedido
Pode ser cancelado

Narrativa Fornecedor & Estoque:
Exposto em aula.

Objetivo:
Refinar o modelo apresentado acrescentando os seguintes pontos:

Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
Entrega – Possui status e código de rastreio;