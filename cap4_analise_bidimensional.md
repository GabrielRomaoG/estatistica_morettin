# Capítulo 4 - Análise Bidimensional

## 4.4 Medidas de Associação entre Variáveis Qualitativas

### Pearson chi-square

Usado para comparar uma observação com o valor esperado dado um hipótese
nula.

$$
    \chi ^ 2 = \sum_{i = 1}^{k} \frac{(O_i - E_i)^2}{E_i}
$$

### Coeficiente de contigência (Contingency Coefficient)

![cap4_analise_bidimensional_2025-08-18_10-16-42](assets/imgs/cap4_analise_bidimensional_2025-08-18_10-16-42.png)

![cap4_analise_bidimensional_2025-08-18_10-17-10](assets/imgs/cap4_analise_bidimensional_2025-08-18_10-17-10.png)

Comparando duas variáveis categórias temos esse chi-square:

Sendo $n_{ij}^ *$, o valor esperado

$$
    \chi ^ 2 = \sum_{i = 1}^{r} \sum_{i = 1}^{s}
    \frac{(n_{ ij } - n_{ ij } ^{ * }) ^ 2}{n_{ ij } ^ { * }}
$$

e o Coeficiente de contigência que deixa num intervalo limitado entre 0 e 1:

1, dependência completa
0, independência

$$
   C = \sqrt{\frac{\chi ^ 2}{\chi ^ 2 + n}}
$$

### Mutual Information

$$
    MI = \sum_{x \in X} \sum_{y \in Y}p(x, y) \log [ \frac{p(x, y)}{p(x) p(y)}]
$$

## 4.5 - Associação entre Variáveis Quantitativas

### Correlação

$$
    corr(X, Y) = \frac{1}{n}\sum_{i = 1}^{n}
    ( \frac{x_i - \overline{x}}{dp(X)} )
    ( \frac{y_i - \overline{y}}{dp(Y)} )
$$

### Covariância

$$
    cov(X, Y) = \frac{\sum_{i=1}^{n} (x_i - \overline{x})(y_i - \overline{y})}{n}
$$

#### Correlação com Covariância

$$
    corr(X, Y) = \frac{cov(X, Y)}{dp(X) \cdot dp(Y)}
$$

## 4.6 Associação entre Variáveis Qualitativas e Quantitativas
