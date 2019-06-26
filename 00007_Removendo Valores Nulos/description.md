Vamos começar a praticar sobre a função de coalesce.

Esta função recebe pelo menos dois valores. O resultado da união será o primeiro dos valores que não é nulo.

`COALESCE (coluna, "Valor padrão")` tentará retornar o valor da coluna escolhida e caso seja **NULL** ele retornará "Valor padrão".

Sua missão é:

> 1. Uma consulta que retorna o nome e o modelo dos produtos

> 2. Se o modelo for nulo, deve dizer "Não aplicável".

> 3. A coluna do modelo, apesar de modificada por uma função, deve ser chamada de "modelo" no resultado. Você pode fazer isso aplicando alias