Similar ao exercício anterior, o resultado que estamos procurando é uma consulta que indica o nome de cada uma das marcas e quantos produtos estão associados a ela. Mas, além disso, vamos adicionar o nome da categoria do produto.

Ou seja, o resultado deve indicar POR MARCA E POR CATEGORIA quantos produtos existem.

Para isso você terá que:

> 1. Fazer um join entre a tabela de produtos e marcas

> 2. Fazer um segundo join entre a tabela de produtos e categorias

> 2. Agrupar os resultados por marca e por categoria

> 3. Inclua os dados necessários no início do SELECT. A ordem correta será primeiro o nome da marca, depois o nome da categoria e finalmente a quantidade. A coluna com o valor deve ser chamada **quantidade**