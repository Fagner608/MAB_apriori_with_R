# Análise exploratória e Market Basket Analisys com APRIORI (R)
Projeto autônomo, visando demonstrar conhecimento teórico e prático nos tópicos descritos abaixo.



- Extração, pré-processamento, análise, visualização, geração de insights, machine learning. O projeto visa aplicar os dados à um modelo de recomendação de compra, calculado com algoritmo APRIORI, encontrando associações entre itens frequentes em compras on-line.

  
Objetivo: em um primeiro momento, conhecer os dados, e, concluir se estão em ordem para aplicação em um modelo. Em um segundo momento, as regras de recomendação serão calculadas e exportadas em um arquivo .csv.


Fonte dos dados: 


1 - Dados foram obtidos no [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx).

## Tecnologias Utilizadas


- R para:

  * Pré-processamento.
  
  * Análise exploratória, visualização e geração de insights.
  
  * Aplicação do modelo (APRIORI)
  
  
  * Principais pacotes utilizados:arules, arulesViz, htmlwidgets, data.table, reshape2, tidyr, dplyr.
 
 
- Conceitos aplicados:

  * Pré-processamento de dados

  * Data-wrangling
    
  * Data-Viz
  
  * Machine learning (com APRIORI)
  
  * Expressões regulares
  
  
## Funcionalidades

- A analise foi conduzida para, ao final, proporcionar a recomendação de compra, por cliente, com grande probabilidade.

## Visualizar


1 - Acesse clicando no arquivo acima com extensão '.ipynb', neste repositório, ou


2 - Faça o clone do repositório para participar deste projeto.

## Resultados


Como resultado da análise, idenfificamos as regras de associação entre os top_10 produtos mais frequentes na lista de compras de clientes, do site em questão:


I - itens frequentes:

![image](https://user-images.githubusercontent.com/96034581/225992647-a69b4033-e199-4b65-9bc5-e257875e683f.png)


II -  Regras:

![image](https://user-images.githubusercontent.com/96034581/225992257-6fc65ee0-e48f-458e-9561-32bb9c3f1a46.png)


Informações relacionadas às vendas puderam ser visualizadas, brevemente, na fase exploratória:

![image](https://user-images.githubusercontent.com/96034581/225992906-ad68b67e-3cc3-4479-a8a1-d16171b02450.png)



![image](https://user-images.githubusercontent.com/96034581/225992964-4a82f6e1-7a8a-4f85-a629-36006c13445a.png)


![image](https://user-images.githubusercontent.com/96034581/225993103-08560cb5-7c5c-4860-b18f-ddae9c81d124.png)


## Conclusão



Como resultado, temos um arquivo contendo a regra mais forte para cada um dos itens mais frequentes da nossa base de dados. Estas informações podem fomentar, por exemplo, e-mails marketing ou recomendações on-line.

## Referências


Fonte dos dados: 


1 - [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx).
