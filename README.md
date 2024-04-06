## ATIVIDADE 1

### 1. Explique, com suas palavras, o que é machine learning?

Machine Learning é um subcampo da IA que se concentra no desenvolvimento
de sistemas capazes de aprender e melhorar seu desempenho autonomamente com base em dados.
Essa capacidade de aprendizado mostra a diferença da programação tradicional, onde os comandos são instruídos.
Poderá ser aplicado, por exemplo, em previsões, recomendações e robótica.

### 2. Explique o conceito de conjunto de treinamento, conjunto de validação e conjunto de teste em machine learning.

No contexto de Machine Learning, os dados são geralmente divididos em três conjuntos: treinamento, validação e teste.

1. **Conjunto de Treinamento**: Este é o conjunto de dados que usamos para treinar nosso modelo. O modelo aprende a
   partir desses dados. É o maior conjunto entre os três, geralmente compreendendo 60-80% do conjunto de dados total.

2. **Conjunto de Validação**: Este conjunto de dados é usado para ajustar os parâmetros (como a taxa de aprendizado para
   algoritmos de aprendizado de máquina) e escolher o melhor modelo durante o treinamento. Ao treinar modelos, podemos
   ter várias iterações e cada iteração produz um modelo diferente. O conjunto de validação nos ajuda a escolher o
   melhor desses modelos. Geralmente é cerca de 10-20% do conjunto de dados total.

3. **Conjunto de Teste**: Este conjunto de dados é usado para avaliar o desempenho do modelo final após o treinamento e
   a validação. Ele nos ajuda a entender como o modelo se comportará com dados novos e não vistos. O conjunto de teste é
   geralmente cerca de 10-20% do conjunto de dados total.

Essa divisão ajuda a evitar o overfitting (quando o modelo se ajusta demais aos dados de treinamento e tem um desempenho
ruim com dados novos) e underfitting (quando o modelo não aprende suficientemente a partir dos dados de treinamento).

### 3. Explique como você lidaria com dados ausentes em um conjunto de dados de treinamento.

Posso optar por excluir as linhas ou colunas com dados ausentes.

Outra opção é preencher os valores ausentes com a média, mediana ou moda dos dados existentes.

Também posso usar técnicas mais avançadas, como imputação de dados, onde os valores ausentes são estimados com base em
outras variáveis do conjunto de dados.

Alguns algoritmos de Machine Learning, como XGBoost, podem lidar com dados ausentes.

A biblioteca pandas fornece métodos para lidar com dados ausentes, como dropna() para excluir e fillna() para imputação.

A biblioteca scikit-learn também fornece a classe SimpleImputer para imputação de dados.

### 4. O que é uma matriz de confusão e como ela é usada para avaliar o desempenho de um modelo preditivo?

### 5. Em quais áreas (tais como construção civil, agricultura, saúde, manufatura, entre outras) você acha mais interessante aplicar algoritmos de machine learning?

## ATIVIDADE 2

### 1. Escreva uma função que receba uma lista de números e retorne outra lista com os números ímpares.

### 2. Escreva uma função que receba uma lista de números e retorne outra lista com os números primos presentes.

### 3. Escreva uma função que receba duas listas e retorne outra lista com os elementos que estão presentes em apenas uma das listas.

### 4. Dada uma lista de números inteiros, escreva uma função para encontrar o segundo maior valor na lista.

### 5. Crie uma função que receba uma lista de tuplas, cada uma contendo o nome e a idade de uma pessoa, e retorne a lista ordenada pelo nome das pessoas em ordem alfabética.

### 6. Observe os espaços sublinhados e complete o código.

    import __________.pyplot as plt
    import numpy as ___
    fig, axs = plt.subplots(ncols=2, nrows=2, figsize=(5.5, 3.5),
    layout="constrained")
    for ___ in range(2):
    for ___ in range(2):
    axs[row, col].annotate(f'axs[{row}, {col}]', (0.5, 0.5),
    transform=axs[row, col].transAxes,
    ha='center', va='center', ________=18,
    color='darkgrey')
    fig.suptitle('__.subplots()')

### 7. Observe os espaços sublinhados e complete o código.

    import numpy as np
    import __________ as mpl
    import __________.______ as plt
    x = np.________(-2 * np.pi, 2 * np.pi, 100)
    y = np.____(x)
    __, __ = plt.subplots()
    ax.____(_, _)

### 8. Utilizando pandas, como realizar a leitura de um arquivo CSV em um DataFrame e exibir as primeiras linhas?

### 9. Utilizando pandas, como selecionar uma coluna específica e filtrar linhas em um “DataFrame” com base em uma condição?

### 10. Utilizando pandas, como lidar com valores ausentes (NaN) em um DataFrame?

