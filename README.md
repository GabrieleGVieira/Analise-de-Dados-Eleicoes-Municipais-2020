
# _Análise de Dados - Eleições Municipais 2020_

> Status do Projeto: Concluído ✅

> Orientador: Profº Fernando Masanori 👨‍🏫

> Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal 🏫

## Nesse trabalho você irá encontrar 

- [Introdução](#introdução)
- [Objetivo](#objetivo)
- [Dados Apresentados](#dados-apresentados)
- [Estados](#estados-com-maior-número-de-casos)
- [Mapa de Casos por Município](#mapa-de-casos-por-município)
- [Eleitorado](#eleitorado-do-grupo-de-risco)
- [Percentual de Eleitores](#percentual-da-idade-dos-eleitores)
- [Conclusão](#conclusão)
- [Desenvolvedoras](#desenvolvedoras)



## Introdução

No ano de 2020, o mundo parou devido a uma pandemia causada por uma doença denominada Covid-19, causada por um vírus da família dos coronavírus, o SARS-Cov-2. 
No dia 11 de Março de 2020, a Organização Mundial da Saúde (OMS) declarou pandemia. Até o final de Março a doença atingiu o número de 846.577 casos confirmados e 41.944 mortes no mundo todo.
Como forma de evitar a propagação do vírus, além de medidas sanitárias individuais, países do mundo todo optaram por Lockdown e fechamento de comércios não essênciais, inclusive o Brasil, a fim de diminuir a circulação de pessoas e controlar a transmissão.
Porém, o ano de 2020 para os brasileiros, também é um ano de eleições municipais. Quando no inicio do segundo semetres de 2020 percebeu-se que a situação ainda não havia melhorado e que o país ainda enfrentava dificuldades para controlar a doença, foi levantado várias questões sobre como seriam as eleições e se poderiam ocorrer de forma segura, principalmente em relação aos grupos de risco.

## Objetivo

Esse trabalho está divido em duas partes. A primeira com o objetivo de analisar o estado com maior número de casos da COVID-19 e também os seus municípios. A segunda parte tem o objetivo de analisar a quantidade de eleitores com mais de 60 anos nessas cidades, e a porcentagem que eles representam em todo o eleitorado.
Essas análises foram feitas afim de ressaltar a necessidade de uma ação estratégica para diminuir a exposição ao risco de contágio dos eleitores do grupo de risco.

## Dados Apresentados

Fonte: [Portal do COVID-19](https://covid.saude.gov.br/), [SEADE](https://www.seade.gov.br/coronavirus/) e [Portal do TSE](https://www.tse.jus.br/hotsites/pesquisas-eleitorais/index.html)

Data dos dados sobre COVID-19: 19/Nov/2020

## Estados com Maior Número de Casos

[Código disponível aqui](https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/Jupyter%20Notebook/PrimeiraParte.ipynb)

Os 5 estados com maior número de casos confirmados de COVID-19 são:

![alt text](https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/img/estados.graf.png)

O estado de São Paulo se destacou demais em relação aos outros estados com maior número de casos, porém como os valores dos outros estados estão próximos, segue o DataFrame para melhor visualização.

![alt text](https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/img/estados.covid.png?raw=true)

## Mapa de Casos por Município

[Código disponível aqui](https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/Jupyter%20Notebook/PrimeiraParte.ipynb)

Os 5 municípios de São Paulo com maior número de casos são:

![alt text](https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/img/cidades.graf.png)

Assim como o gráfico anterior, a cidade de São Paulo se destaca a frente das outras cidades, enquanto essas aparentam valores bem próximos. 

![alt text](https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/img/cidades.covid.png)

## Eleitorado do Grupo de Risco

[Código disponível aqui](https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/Jupyter%20Notebook/SegundaParte.ipynb)

A quantidade de eleitores com mais de 60 anos pode ser análisada pelo gráfico a seguir

![alt text](https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/img/eleitores.idosos.png)

O gráfico nos aponta uma diferença bem grande entre a cidade de São Paulo e as outras cidades. Porém, as nossas outras quatro cidades estão com valores aproximados, por isso iremos analisar os valores no DataFrame.

![alt text](https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/img/tabela.eleitores.png)

Como esperado, São Paulo é a cidade com o maior número de eleitores idosos, isso provavelmente se deve a quantidade de pessoas que residem na cidade, que é um número bem maior comparado as outras. Por conta disso, também iremos analisar as cidades separadamente, relacionando a porcentagem de idosos para o número total de eleitores.

## Percentual da idade dos eleitores

[Código disponível aqui](https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/Jupyter%20Notebook/SegundaParte.ipynb)

<img src="https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/img/idosos.sp.png" width=700 > <br> <sub> Cidade de São Paulo </sub> | <img src="https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/img/idosos.camp" width=700> <br> <sub> Cidade de Campinas </sub> |
| :---: | :---: | 

<img src="https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/img/idosos.sjrp.png" width=700 > <br> <sub> Cidade de São José do Rio Preto </sub> | <img src="https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/img/idosos.sbc.png" width=700> <br> <sub> Cidade de São Bernardo do Campo </sub>|
| :---: | :---: |


<img src="https://github.com/GabrieleGVieira/Analise-de-Dados-Eleicoes-Municipais-2020/blob/main/img/idosos.rp.png" width=450 > <br> <sub> Cidade de Ribeirão Preto </sub> | 
| :---: | 


Diferente do outro gráfico, ao analisarmos cada cidade separadamente, vemos que a quantidade de eleitores idosos em relação ao número total de eleitores ficaram muito próximos uma das outras, com uma diferença até descartavél. E em todas as cidade, podemos perceber que o grupo de eleitores idosos representam mais da metade do eleitorado total.

## Conclusão

Vale resaltar que, o voto para quem tem mais de 60 anos não é obrigatório, porém votar é um direito civil de todos os cidadãos, e fazer isso com segurança também é. O fato de estarmos em uma pandemia em um ano eleitoral não muda isso, mas nos obriga a nos adaptarmos para essa situação. Tendo visto que, mais de 50% do eleitorado em cidades com alto indice de casos da COVID-19 tem mais de 60 anos, sendo esses classificados como grupo de risco, se torna necessário medidas especiais para manter a segurança desse grupo no ambiente de votação, afim de diminuir o risco de exposição ao vírus. Essas medidas irão influenciar principalmente na decisão desses eleitores em ir votar, evitando assim uma grande evasão eleitoral. Então,além de campanhas de conscientização sobre as medidas de proteção, o fato do horário de votação iniciar mais cedo e com um horário especial para os idosos, determinado pela Justiça Eleitoral, tem um enorme valor no combate a essa evasão e no dever de oferecer segurança na hora de exercer o direito de votar. 

## Desenvolvedoras

[<img src="https://avatars1.githubusercontent.com/u/71100287?s=400&u=1c3492ca193736aafed77b90f5a49678dd50975e&v=4" width=115 > <br> <sub> Gabriele Vieira </sub>](https://github.com/GabrieleGVieira) | [<img src="https://avatars2.githubusercontent.com/u/72801105?s=400&u=f72042dd40d93e5b594b527b6605fcbd3669c510&v=4" width=115 > <br> <sub> Sarah Santana </sub>](https://github.com/Sarah781) |
| :---: | :---: | 


