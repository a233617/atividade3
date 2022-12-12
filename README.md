# atividade3
Tarefa 3 - Testes Estatísticos

a)

Resposta 1: 

Wilcoxon, e T

Diabéticos:
median    76.000000
mean      74.588235

Não Diabéticos:
median    70.000000
mean      69.545455

T= Ttest_indResult(statistic=3.001495202122035, pvalue=0.0030323591864622732)

Resposta 2:

Diabéticos têm maior pressão média, e também pressão mediana

Respota 3:

A diferença não é significativa. O p-valor é muito baixo. Dessa forma, é possível afirmar com alguma evidência que os conjuntos de dados são realmente diferentes, com 95% de confiança.

O teste Wilcoxon pode ser uma boa alternativa ao teste t quando os meios populacionais não são importantes; 
por exemplo, quando se pretende testar se a mediana de uma população não é zero, ou se existe uma probabilidade 
superior a 50% de que uma amostra de uma população seja maior do que uma amostra de outra população.
Neste caso, o teste Wilcoxon sse mostra mais apropriado 

b)

Resposta 1:

Wilcoxon, e T pareado

Agosto:
median    10.000000
mean      11.423077

Novembro:
median    15.300000
mean      16.323077

T= Ttest_indResult(statistic=-5.819709111181409, pvalue=0.028279069072247292)

Em Agosto, tanto a média quanto a mediana foi menor que Novembro

O teste t parece ser mais apropriado que Wilcoxon


c)

O intervalor de confiança para as duas amostras foi

ConfidenceInterval(low=70.0, high=78.0)
ConfidenceInterval(low=68.0, high=72.0)

Está parecido com aquilo que foi visto na questão 1

d)

Teste de Cohen d

Diabéticos: -4.0723633181394945
Não diabéticos: -3.968437710042257

Pelo que vi publicado (eu próprio, sou diabético a 20 anos, mas tenho a pressão normal), e conversando com uma nutricionista 
(Ludmila Pereira de Souza, CRN 11 2064), é possível afirmar que diabéticos podem ter pressão sanguínea maior. Mas não é uma garantia, uma certeza, mas é uma 
tendência. Tem muitas variáveis, depende muito  do estilo de vida  do indivíduo - Isso é o fator determinante. Quanto melhor for o estilo de vida, a qualidade da alimentação, melhor, mais dificilmente a pressão alta virá ou pelo menos, será adiada.

