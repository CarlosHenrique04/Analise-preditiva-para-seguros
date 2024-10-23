Análise de Modelos de Regressão

Este repositório contém uma análise abrangente de modelos de regressão para prever despesas de saúde com base em características demográficas e socioeconômicas. Utilizando bibliotecas populares de Python como pandas, numpy, scikit-learn, e matplotlib, este projeto se concentra em três algoritmos de aprendizado de máquina: Regressão Linear, Random Forest e K-Nearest Neighbors (KNN).

Objetivos do Projeto

Previsão de Despesas: O objetivo principal é prever as despesas de saúde de indivíduos com base em dados disponíveis, utilizando técnicas de aprendizado de máquina.

Avaliação de Modelos: Os modelos são avaliados utilizando métricas de desempenho, incluindo RMSE (Root Mean Squared Error) e acurácia, para determinar sua eficácia.

Otimização de Hiperparâmetros: O projeto implementa uma busca em grade para otimizar hiperparâmetros do modelo Random Forest, visando melhorar o desempenho preditivo.

Estrutura do Código

Importação de Bibliotecas: Bibliotecas necessárias são importadas.

Carregamento e Pré-processamento dos Dados: Os dados são carregados e pré-processados, incluindo a separação em conjuntos de treino e teste.

Definição dos Modelos: Os modelos de Regressão Linear, Random Forest e KNN são definidos.

Treinamento e Validação: Os modelos são treinados e validados utilizando validação cruzada e são calculadas as métricas de desempenho.

Otimização de Hiperparâmetros: O modelo Random Forest é otimizado através de Grid Search.

Avaliação Final: As previsões são feitas no conjunto de teste e as métricas de desempenho são apresentadas, incluindo RMSE e acurácia.

Conclusão

Este projeto fornece uma base sólida para entender como aplicar técnicas de aprendizado de máquina na previsão de despesas de saúde e avaliar a eficácia dos modelos utilizados. A análise das métricas de desempenho ajuda a identificar qual modelo oferece as melhores previsões e como ajustes podem melhorar os resultados.
