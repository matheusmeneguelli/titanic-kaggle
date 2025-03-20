# Previsão de Sobrevivência no Titanic

Este repositório contém um projeto de Machine Learning aplicado ao clássico conjunto de dados do Titanic. O objetivo é demonstrar como aplicar um modelo de classificação para prever quais passageiros sobreviveram ao naufrágio, além de explicar as técnicas utilizadas para avaliação do desempenho do modelo.

## Descrição do Projeto
O conjunto de dados do Titanic é amplamente utilizado para aprendizado em ciência de dados, pois permite a aplicação de diversos conceitos de pré-processamento, modelagem e avaliação de algoritmos de Machine Learning.

Neste projeto, utilizamos Random Forest como modelo preditivo, aplicando RandomizedSearchCV para otimização de hiperparâmetros e K-Fold Cross Validation para validação. A avaliação do modelo inclui:
Matriz de confusão e suas métricas (acurácia, precisão, recall e F1-score)
Curva ROC e coeficiente de Gini para medir a performance da classificação

Ao final, as previsões são exportadas em formato CSV para submissão no Kaggle.

Referências: [Desafio Titanic no Kaggle](https://www.kaggle.com/competitions/titanic)
