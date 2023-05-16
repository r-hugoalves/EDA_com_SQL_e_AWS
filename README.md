# Exploração e análise de dados de crédito com SQL

**Nesse estudo, vamos analisar um conjunto de dados que representam informações de clientes de um banco.**

Para o nosso estudo, vamos utilizar as ferramentas S3 e Athena da AWS e uma parte do conjunto de dados disponibilizados [nesse](https://github.com/andre-marcos-perez/ebac-course-utils/tree/main/dataset) repositório*. Além disso, todos os gráficos aqui apresentados foram gerados utilizando o excel.
O conjunto em específico que vamos utilizar pode ser obtido [aqui](https://github.com/r-hugoalves/EDA_com_SQL_e_AWS/blob/master/planilha_geral.csv).
<br>

**.: não vamos trabalhar com todo o conjunto de dados para não ultrapassar o período gratuito da AWS. Por isso, utilizaremos apenas as 2563 primeiras linhas.*

**Legenda dos dados presentes na tabela:**

* idade = idade do cliente
* sexo = sexo do cliente (F ou M)
* dependentes = número de dependentes do cliente
* escolaridade = nível de escolaridade do clientes
* salario_anual = faixa salarial do cliente
* tipo_cartao = tipo de cartao do cliente
* qtd_produtos = quantidade de produtos comprados nos últimos 12 meses
* iteracoes_12m = quantidade de iterações/transacoes nos ultimos 12 meses
* meses_inativo_12m = quantidade de meses que o cliente ficou inativo
* limite_credito = limite de credito do cliente
* valor_transacoes_12m = valor das transações dos ultimos 12 meses
* qtd_transacoes_12m = quantidade de transacoes dos ultimos 12 meses

[Notebook do projeto](https://colab.research.google.com/drive/1W-YLnW3xDe7G4DWDf6JamN4UDY4prr2b?usp=sharing)
