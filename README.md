Análise de Modelos de Regressão para Previsão de Despesas

Este repositório contém um projeto de análise de dados que aplica três modelos de regressão (Random Forest, Regressão Linear e K-Nearest Neighbors) para prever despesas com base em um conjunto de dados de custos. O objetivo principal é avaliar a eficácia de cada modelo utilizando métricas de erro, como o RMSE (Root Mean Squared Error), e calcular a acurácia e a matriz de confusão.

Metodologia

Preparação dos Dados: 
Os dados foram carregados e preparados, incluindo a separação em conjuntos de treinamento e teste. As variáveis de entrada e saída foram definidas, e a normalização foi aplicada conforme necessário.

Modelagem: Foram utilizados três modelos de aprendizado de máquina:

Random Forest: Um modelo de ensemble que utiliza múltiplas árvores de decisão para melhorar a precisão e controlar o overfitting.
Regressão Linear: Um modelo simples que assume uma relação linear entre as variáveis independentes e dependentes.
K-Nearest Neighbors (KNN): Um modelo baseado em instâncias que classifica os dados com base nas características dos vizinhos mais próximos.
Avaliação do Modelo: A validação cruzada foi aplicada para avaliar o desempenho de cada modelo, e o RMSE foi calculado como uma medida de erro. Para melhor compreensão da eficácia dos modelos, a acurácia e a matriz de confusão foram calculadas, transformando as previsões contínuas em categorias binárias.

Resultados: Os resultados são apresentados com a média do RMSE para cada modelo e a respectiva acurácia, além da visualização das matrizes de confusão para uma análise mais detalhada do desempenho.
