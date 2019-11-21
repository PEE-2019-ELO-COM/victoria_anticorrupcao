# victoria_anticorrupcao

O projeto tem o objetivo de criar um programa em python que interprete dados de despesa, receita, favorecidos por gastos, parcerias e contratos do Rio de Janeiro em 2019 para identificar possíveis atividades ilícitas. Os dados utilizados foram recolhidos do github do Hackfest e podem ser consultados no link a seguir:
https://github.com/mp-rj/dados-hackfestcc

A motivação era aprender do zero sobre data science, algo que acredito que vai me ajudar na vida profissional, em um projeto envolvente e que tem disponível muitas fontes para consulta.

# Escolha da biblioteca gráfica

Por se tratar de um projeto de ciência de dados a escolha da biblioteca gráfica apresentou algumas dificuldades, principalmente pelo desenvolvimento do código estar sendo feito em Google Colab, o que não era o planejado inicialmente. Como a biblioteca utilizada para análise de dados é a Pandas, escolheu-se a biblioteca Bamboo para gerar a GUI. Não foram encontrados tutoriais na internet, apenas vídeos exibindo como ela pode ser utilizada. Os links dos vídeos seguem abaixo:
https://www.youtube.com/watch?v=y5F4Brf7FBs

https://www.youtube.com/watch?v=I0a58h1OCcg

# Fluxograma

Os dados escolhidos para serem analisados foram:

1. Contratos
Com esses dados há a possibilidade verificas as pessoas/empresas mais favorecidas com contratos, ver os contratos que sofreram mais acréscimos durante o tempo de execução e as contratos com o mesmo tipo de depesa repetidamente.

2. Despesas
Com esses dados é possível observar gastos repetitivos e os orçamentos de projetos mais distantes da média.

3. Favorecidos
Há a possibilidade de verificar pessoas que aparecem mais vezes entre os gastos, além dos favorecidos com maior volume de gastos e despesas pontuais muito acima da média.

4. Parcerias
Possibilidade de verificar quais parceiros recebem mais dinheiro, CNPJs que mais aparecem entre os parceiros, podendo verificar no futuro se eles CNPJs são de fato verdadeiros.

5. Receita
Pode-se verificar quais receitas arrecadas estão mais baixas que o esperado, além da existência de algum mês em especial que os valores arrecadados foram bem menores que a média.





