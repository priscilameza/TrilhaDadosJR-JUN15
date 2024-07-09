Etapadas de trabalho análise de dados
-> utilizei o google.colab pela facilidade de compartilhamento
1º Salvei os dados fornecidos como um arquivo .csv
2º Instalei jupyter, pandas e importei
3º Abri o arquivo .csv e identifiquei os tipos de dado de cada coluna. Por meio dessa análise percebi alterações necessárias:
  ID(int) como não seria utilizado para contas, considerei o tratamento para str
  DATA(object) para facilitar o trabalho de análise e filtragem de dados, considerei o tratamento para formato de data
4º realizei o tratamento dos dados necessários

DESAFIO 1:
1º criei uma nova coluna realizando a multiplicação do custo unitário dos cursos pela quantidade de cursos vendida, obtendo o Total de arrecação por curso
2º realizei a soma simples de todos valores da nova coluna, obtendo o total gerado pela venda dos cursos: 32.735,10
  arredondei o valor da soma para duas casas decimais para facilitar compreensão

DESAFIO 2:
1º utilizei o describe para identificar o maior valor de vendas (50)
2º utilizei filtragem de dados para retornar apenas a linha que possuísse valor = 50 na coluna Quantidade de Vendas
3º repeti o código com a opção >= 50 para confirmar que não havia nenhuma linha com valor maior

DESAFIO 3:
-> como nessa tabela cada venda está lançada em uma data diferente, não foi necessário usar o Group By para realizar a soma por dia.
  Grafico 1: barras
  mostra o valor total de vendas por dia

  Grafico 2: linhas
  mostra a quantidade de vendas realizada por dia

  Grafico 3: dispersão
  mostra a relação entre quantidade de vendas e valor total arrecadado.
  -> por meio desse gráfico foi possível notar, por exemplo, que o curso que mais faturou não foi o curso que mais vendeu.
