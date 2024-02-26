# ...em construção...


# Olá! 💜
# Seja bem-vindo à análise de dados de um e-commerce dos Estados Unidos.

_A análise foi baseada no dataset presente no link: https://www.kaggle.com/datasets/juhi1994/superstore_

**Resumo**

Projeto final do curso de Data Science que consiste em apresentar dados de um e-commerce a fim de analisar as vendas, explorar dados atrelados a essas vendas e desenvolver um modelo de machine learning. 

**Racional utilizado**

1. Importação e análise do Dataset
2. Limpeza dos dados: deletei algumas colunas que acreditei que “sujariam” a análise
3. Verificação se há valor nulo e os types para alteração deles caso necessário
4. Levantar questionamentos a serem respondidos através da análise
5. Análise das vendas por ano e categoria

➡️Questionamentos levantados:

_Os questionamentos consistem em analisar o período, valores e categorias dos produtos vendidos. Respondendo quando, quanto e qual._

**Qual a data(Order Date) mínima e máxima presente no dataset?**
Isso ajuda a entender qual o tamanho do período desses dados. 

**Qual a média e desvio padrão das vendas e do lucro decorrente dessas vendas?**
Isso ajuda a entender se houve muita diferença entre os valores e o porte do e-commerce tratado.

**Qual ano aparece com mais frequência?** 
Isso ajuda a entender qual ano teve maior volume de vendas.

**Qual categoria foi mais vendida considerando todos os anos?** 
Isso ajuda a entender o tipo de produto que teve mais saída. 

**Qual o valor de vendas por ano?** 
Isso ajuda a entender qual oscilação ocorreu por ano e qual o que teve maior maior valor de venda.

**No ano com maior número de vendas, qual foi a categoria mais vendida  em termos de quantidade e valor?** 
Isso ajuda a entender a representatividade de cada categoria neste ano de maior sucesso em relação aos outros.

**Além da categoria mais vendida, qual foi a categoria que mais gerou lucro?** 
Isso mostra que volume e valor de venda por si só não determina lucro, que é o que mais sustenta um sistema de um e-commerce. 


**Bibliotecas e tecnologias utilizadas**:

✅Python
✅Matplotlib
✅Pandas
✅Seaborn 
✅Scikit-learn

_____________________________________________________________________________________________________________________________

#Começo importando as bilbiotecas antes de importar o dataset
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np

#Lendo o arquivo através do caminho do drive
df1=pd.read_csv ("/content/drive/MyDrive/Projeto Data Science/US Superstore data.xls - Orders.csv")


