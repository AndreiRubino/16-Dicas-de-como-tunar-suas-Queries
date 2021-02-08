# 16 Dicas de como tunar suas Queries

Este artigo tem como objetivo informar boas práticas de Tuning de Querys, a fim de melhorarmos o desempenho das Querys. As dicas abaixo não garantem por si só um melhor desempenho, cada query deve ser analisada a parte com base na sua necessidade.

-	Não criei índices para tabelas pequenas.
-	Criei índices somente para consultas frequentes.
-	Utilize Index nas FKs.
1.	Evite utilizar funções em colunas do SELECT.
2.	Evite utilizar funções nas colunas da clausula JOIN.
3.	Evite usar funções de conversão em colunas com índice. 
•	Evite conversões implícitas, prefira conversões explicitas. 
•	Evite comparar valores com NULL.
•	Evite Operadores de negação.
•	Evite Operadores LIKE com % no inicio da string. 
•	Evite utilizar DISTINCT quando puder usar o EXISTS.
•	Utilize o EXISTS se o where estiver na outer query, utilizee IN se o where estiver na inner query.
•	Utilize Alias em consultas com colunas ambíguas.
•	Utilize os Operadores de Precedência com melhor nível de execução.
•	Evite asterisco na instrução SELECT.
•	Sempre que possível utilize o ROWNUM.

Em breve estarei escrevendo artigos com mais dicas e também exemplos práticos.


- Bulleted
- List

1. Numbered
2. List
