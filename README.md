![360_F_245446598_ufTQ88c6bRk7ZRAfcJcfDF9B5Cn5UumE](https://user-images.githubusercontent.com/91103250/222302112-cd9f9cf3-5cba-47ae-9726-51e180ff797e.jpg)



# Previsão com Séries Temporais - Algoritmo Prophet
O objetivo dessa análise é fazer uma previsão para os próximos 365 dias da temperatura média na região de Jena, Alemanha. Para esse projeto foi utilizada uma base de dados disponível no Kaggle com as medições entre Jan/2009 e Dez/2016.

Para tal análise será utilizado o algoritmo Prophet que é disponibilizado pelo time de Ciência de Dados do Meta. 

## Informações do dataset
O conjunto de dados Jena Climate é composto por 14 atributos diferentes (como temperatura do ar, pressão atmosférica, umidade, direção do vento e assim por diante) registradas a cada 10 minutos, ao longo de vários anos. Este conjunto de dados abrange dados de 1º de janeiro de 2009 a 31 de dezembro de 2016.

#### Fonte do dataset: https://www.kaggle.com/datasets/mnassrib/jena-climate

## Dicionário de Dados
| Atributo | Descrição | Métrica |
| ------------- | ------------- | ------------- |
| Date Time  | Data e Hora das medições  | DateTime  |
| p (mbar)  | A unidade de pressão derivada de Pascal SI usada para quantificar a pressão interna. Relatórios meteorológicos tipicamente estaduais a pressão atmosférica em milibares  | Numérico  |
| Date Time  | Data e Hora das medições  | Numérico  |
| Date Time  | Data e Hora das medições  | Numérico  |
| Date Time  | Data e Hora das medições  | Numérico  |
| Date Time  | Data e Hora das medições  | Numérico  |
| Date Time  | Data e Hora das medições  | Numérico  |
| Date Time  | Data e Hora das medições  | Numérico  |
| Date Time  | Data e Hora das medições  | Numérico  |
| Date Time  | Data e Hora das medições  | Numérico  |
| Date Time  | Data e Hora das medições  | Numérico  |
| Date Time  | Data e Hora das medições  | Numérico  |
