Vamos lembra da tabela vendas:

<div
  class='mu-erd'
  data-entities='{
    "vendas": {
      "id": {
        "type": "Integer",
        "pk": true
      },
      "id_cliente" : {
        "type": "Integer"
      },
      "id_produto" : {
        "type": "Integer"
      }
    }
  }'>
</div>

Esta tabela é uma tabela intermediária para denotar o relacionamento de muitos para muitos entre produtos e clientes.

**id_cliente ** é uma chave estrangeira para a tabela de clientes e **id_produto ** é uma chave estrangeira para a tabela de produtos.

Seu desafio é o seguinte:

> 1. Faça uma consulta que traga o nome e sobrenome dos clientes e o nome dos produtos que compraram

> 2. Se os clientes não compraram nenhum produto, eles também devem aparecer no resultado