A biblioteca criada contem as seguintes funções: 
- PoliRegFit: Função criada para realizar regressão polinomial. Aceita dois métodos, mínimos quadrados ordinários ou mínimos quadrados ponderados.
- LOESS: A função percorre todo o espectro e suavisa o espectro ponto a ponto através do método dos mínimos quadrados ponderados.
         Realiza dirverssos WLS's ao longo do espectro.
- BasePolyCor: Cria curvas polinomiais consecutivas para ajustar o baseline dos espectros
- LDAcald: Cálculo de vetores discriminantes, recebe scores prontos obtidos de um SVD e a classe de valores que se deseja constratar em um eixo linear.
- sep_sort: Divide um grupo de amostras em outros n grupos, de forma aleatória e balanceada, ou seja, cada novo grupo terá quantidades balanceadas de amostras de cada classe
- AUC: Area Under the Curve. Calcula a probabilidade de uma amostra classificada como "positiva" ter valor de score maior que uma amostra negativa após a projeção de seus scores em um
       vetor discriminante
- RDCV3: Realiza a validação crusada de um modelo de PCA- LDA. É A FUNÇÃO PRINCIPAL DESSE REPOSITÓRIO 
