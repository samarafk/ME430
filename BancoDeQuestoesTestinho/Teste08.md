# Teste 8


## Exercício 1



Para estimar o número médio de árvores por acre em uma plantação com 1000-acres, o investigador usa uma $AAS_s$ de 10 áreas com 1 acre cada e conta o número de árvores ($y$) em cada área. O investigador também tem fotos aéreas da plantação, a partir das quais ela pode obter o número de árvores aproximado ($x$) por acre para a plantação toda. Portanto, o investigador sabe que $\mu_x=19.7$. Como as duas variáveis, $x$ e $y$, são aproximadamente proporcionais e, além disso, se uma variável é 0 a outra também será, o investigador deseja usar estimadores do tipo razão. A seguir estão os dados coletados, $x$ e $y$ e o cálculo da variável: $y-rx$, onde $r$ é a estimativa de $R=\mu_y/\mu_x$.


 Area    y    x         y-rx
-----  ---  ---  -----------
    1   22   23   -1.9951923
    2   16   14    1.3942308
    3   21   20    0.1346154
    4   28   25    1.9182692
    5   12   12   -0.5192308
    6   17   18   -1.7788462
    7   28   30   -3.2980769
    8   30   27    1.8317308
    9    9    8    0.6538462
   10   34   31    1.6586538

Para facilitar os cálculos, você pode usar a seguinte informação:


                 y       x   y-rx
----------  ------  ------  -----
media        21.70   20.80   0.00
variancia    67.79   60.62   3.39


1. Estime o número médio de árvores por acre na plantação usando a média amostral. Estime a variância da estimativa.

2. Estime o número médio de árvores por acre na plantação usando estimador do tipo razão. Estime a variância da estimativa.

3.  Estime o número total de árvores na plantação usando estimador do tipo razão. Estime a variância da estimativa.

4. Encontre o tamanho amostral necessário para que a diferença entre o número médio de árvores por acre na população e a respectiva estimativa usando o estimador de razão não exceda 1 com 95\% de confiança. Para os cálculos, assuma por um instante que $S_R^2=s_R^2$. Atente-se para o fato de que o plano amostral é $AAS_s$.


## Exercício 2






Um fazendeiro fez uma avaliação grosseira da produção $x_i$, em kg, de cada um de seus $N=210$ pessegueiros. A peso total foi $5800$ kg segundo a avaliação grosseira do fazendeiro. Tomou-se uma $AAS_s$ de 10 pessegueiros, colheram-se os pêssegos e pesou-se a produção $y_i$. Os resultados estão abaixo. Para facilitar os cálculos, os resultados da variável $y-rx$ estão incluídos.


 Pessegueiro    y    x         y-rx
------------  ---  ---  -----------
           1   30   30    1.7832168
           2   21   24   -1.5734266
           3   25   26    0.5454545
           4   29   30    0.7832168
           5   34   34    2.0209790
           6   22   24   -0.5734266
           7   19   22   -1.6923077
           8   28   29    0.7237762
           9   35   38   -0.7412587
          10   26   29   -1.2762238

$$\sum_{i=1}^nx_i=286$$

$$\sum_{i=1}^ny_i=269$$

$$\sum_{i=1}^nx_iy_i= 7922$$

$$\sum_{i=1}^nx_i^2= 8394$$

$$\sum_{i=1}^ny_i^2= 7493$$

$$\hat{\rho}(x,y)=0.9740512$$


                 y       x   y-rx
----------  ------  ------  -----
media        26.90   28.60   0.00
variancia    28.54   23.82   1.84

1. Estime o total da produção usando $N\bar{y}$. Estime a variância da estimativa.

2. Estime o total da produção usando estimador do tipo razão. Estime a variância da estimativa.

3. Estime o total da produção usando estimador do tipo regressão. Estime a variância da estimativa.


Fonte: Baseado no Exercício 6.3 do livro *Elementos de Amostragem* - Bolfarine \& Bussab.
