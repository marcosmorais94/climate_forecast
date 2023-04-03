![360_F_245446598_ufTQ88c6bRk7ZRAfcJcfDF9B5Cn5UumE](https://user-images.githubusercontent.com/91103250/222302112-cd9f9cf3-5cba-47ae-9726-51e180ff797e.jpg)



# Previsão com Séries Temporais - Algoritmo Prophet
O objetivo dessa análise é fazer uma previsão para os próximos 365 dias da temperatura média na região de Jena, Alemanha. Para esse projeto, foi utilizada uma base de dados disponível no Kaggle com as medições entre Janeiro/2009 e Dezembro/2016.

Para tal análise, será utilizado o algoritmo Prophet que é disponibilizado pelo time de Ciência de Dados do Meta. Para avaliação do modelo será usado o erro médio.
O modelo precisa prever as temperaturas diárias com base na sazonalidade do clima europeu, com pico do verão em julho e inverno em janeiro.

## Informações do dataset
O conjunto de dados Jena Climate possui 14 atributos diferentes (como temperatura do ar, pressão atmosférica, umidade, direção do vento e assim por diante) registradas a cada 10 minutos, ao longo de vários anos. Este conjunto de dados abrange dados de 1º de janeiro de 2009 a 31 de dezembro de 2016.

#### Fonte do dataset: https://www.kaggle.com/datasets/mnassrib/jena-climate

## Dicionário de Dados
| Atributo | Descrição | Métrica |
| ------------- | ------------- | ------------- |
| Date Time  | Data e Hora das medições  | DateTime  |
| p (mbar)  | A unidade de pressão derivada de Pascal SI usada para quantificar a pressão interna. Relatórios meteorológicos tipicamente estaduais a pressão atmosférica em milibares  | Numérico  |
| T (degC)  | Temperatura em Celsius (ºC)  | Numérico  |
| Tpot (K)  | Temperatura em Kelvin (K)  | Numérico  |
| Tdew (degC)  | Temperatura em Celsius em relação à umidade. O Dew Point é uma medida da quantidade absoluta de água no ar, o DP é a temperatura na qual o ar não pode manter toda a umidade nela e a água condensa  | Numérico  |
| rh (%)  | A umidade relativa é uma medida de quão saturada o ar está com o vapor de água, o rh % determina a quantidade de água contida nos objetos de coleta | Numérico  |
| VPmax (mbar)  | Pressão de vapor de saturação  | Numérico  |
| VPact (mbar)  | Pressão de vapor  | Numérico  |
| VPdef (mbar)  | Déficit de pressão de vapor  | Numérico  |
| sh (g/kg)  | Umidade específica  | Numérico  |
| H2OC (mmol/mol)  | Concentração de vapor de água  | Numérico  |
| rho (g/m ** 3)  | Hermético  | Numérico  |
| wv (m/s)  | Velocidade do vento  | Numérico  |
| max. wv (m/s)  | Velocidade máxima do vento  | Numérico  |
| wd (deg)  | Direção do vento em grau  | Numérico  |


Informações do Dataset:
|  | |
| ------------- | ------------- |
| Total de Registros  | 420.551  |
| Total de Atributos  | 14  |
