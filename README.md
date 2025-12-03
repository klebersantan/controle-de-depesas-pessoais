# controle-de-depesas-pessoais
Controle de dispesas

# lP2025-2
kleber

#Oque foi usado para impliementar o código:
#import  pandas as pd # essas são importação para uso do bloco de código
#  import os para uso do bloco de código exemplo try, def que é o dataframe 

# as intalações e  versões do panda
 pip install openpyxl - a versão atualiazada openpyxl==3.1.0
 mais versão que usamos foi uma anterior a essa = pandas==2.2.3 e também openpyxl==3.3.1

 # os erros sobre Exportar um novo arquivo Excel com um resumo de gastos por categoria
 os erros era de não declarar um novo código dataframe com resumo_gasto_por_categoria(df)
 isso inicia nosso código e também de exporta um novo arquivo excel como resumo_gastos_xlsx, que essa forma de exporta o arquivo 

 # sobre Somar os gastos por categoria
 vai na mesma linha de fazer uma nova variavél de somar gastos usando  (sum) e os gastos por (categoria)que é sum(soma).reset_index()
 então ficaria dessa forma ex: def somar_gastos_por_categoria(df) usando dataframe, não irie coloca código todo até por que seria bem masi   facil para vcs fazerem , mais aqui está um resumo.
