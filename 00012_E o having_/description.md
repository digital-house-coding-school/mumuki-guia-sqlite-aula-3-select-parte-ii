Mais uma vez, vamos procurar o número de produtos por categoria e marca... só queremos ver linhas que tenham pelo menos dois produtos.

Para isso você terá que:

> 1. Fazer um join entre a tabela de produtos e marcas

> 2. Fazer um segundo join entre a tabela de produtos e categorias

> 2. Agrupar os resultados por marca e por categoria

> 3. Dizer com **having** que só queremos ver os resultados que tenham pelo menos 2 produtos.

> 4. Inclua os dados necessários no início do SELECT. A ordem correta será primeiro o nome da marca, depois o nome da categoria e finalmente a quantidade. A coluna com o valor deve ser chamada **valor**