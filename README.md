# pandas-testando-e-analisando

Neste notebook estou estudando a biblioteca Pandas do python, possui tanto conteúdo da plataforma Alura quanto conteúdo de minha autoria.

## Neste notebook foi estudado os seguintes itens: 

- Importar dados e exportar dataframes
    - Como importar a biblioteca (`import pandas as pd`)
    - Leitura de base de dados diferentes ( CSV, JSON, TXT, Excel, HTML)
    - Exportação e gravar os dados do dataframe (Ex de um método `to_csv`)

- Limpando e tratar dados faltantes
    - Eliminar duplicatas pelo método `drop_duplicates()`
    - Redefinição de index de um dataframe ou series (pelo atributo `index`)
    - Concatenação de dataframes (`axis`)
    - Identificar valores nulos (`isnull()` , `info`)


- Remover outliers e criar novas variáveis
    - Remoção de valores nulos com o método `dropna()`
    - Substituição de missing values com `fillna()`
    - Exclusão de variáveis utilizando `del`,`pop()` e `drop()`
    - Renomeação de colunas com `rename()`
    - Criação de faixas de valores com `cut()`
    - Tratar outliers com boxplot

- Selecionar e gerar frequencias dos dados
    - Contadores com `value_counts()`
    - Estatísticas descritivas com `describe()` e `aggregate()`
