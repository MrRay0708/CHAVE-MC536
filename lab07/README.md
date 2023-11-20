# Lab.07
## Modelo lógico
![Modelo](https://github.com/MrRay0708/MC536-CHAVE/blob/main/lab07/lab07.png)

## Perguntas
* Quais receitas são mais semelhantes entre si?
  * Como no modelo temos um grafo bipartido, podemos relacionar a tabela Receitas com ela mesma, utilizando a propriedade de reflexão para criar uma terceira tabela e poder relacionar as receitas entrew si para assim compará-las e obter o número de ingredientes em comum entre cada uma.
* Em quantas receitas aparece tal ingrediente com devido modo de preparo?
  * Similarmente a primeira questão, utilizariamos a propriedade da reflexão, todavia teríamos de comparar, nesta ocasião, a tabela Alimento com ela mesma, para criar uma relação de comparação através das receitas as quais compartilham e estão contidas. Entretanto teríamos uma projeção condicionada pelo modo de preparo do ingrediente.
* Quais alimentos tal receita tem em comum com todas suas variações?
  * Esta problemática pode ser resolvida com uma projeção da intersecção de todas variações de uma mesma receita dentro da tabela Receita-Alimento. Com a finalidade de descobrir quais alimentos estão presentes em todas versões de um mesmo prato.
