# Geographical Scattering of Votes in Brazil

This is an experiment on generating maps using the "G" index for calculating geographical scattering of votes in Brazil. 

The article [Geographical Scattering of Votes in Brazilian Elections (1994-2014)](https://www.scielo.br/j/dados/a/FjxvsM9jJPfVhX58gKLrgpv/?lang=pt), published in 2016 by George Avelino, Ciro Biderman and Glauco Peres da Silva in the journal *Dados - Revista de Ciências Sociais*, defends the use of a new indicator of geographical scattering of votes. The results showed that successful candidates had their votes more scattered than the defeated ones, contradicting theories which suppose the predominance of votes for individuals in proportional Brazilian elections.

This repository contains an application of the indicator created by the authors - the "G" index. I explain the mathematical formula used to calculate it, its practical interpretation and then I develop the pipeline to plot some maps using it. The congressperson whose data was used to perform the analysis is completely random, except for the fact that he/she was elected in both 2018 and 2022 in the state of Rio de Janeiro.

The data was accessed through [Base dos Dados](). In particular, these 2 sets of data: [Eleições Brasileiras](https://basedosdados.org/dataset/br-tse-eleicoes?bdm_table=bens_candidato) and [Dados Geográficos Brasileiros (geobr)](https://basedosdados.org/dataset/br-geobr-mapas?bdm_table=setor_censitario_2010).
