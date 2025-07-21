# deep-learning-exercicio3

Este repositório agrupa os notebooks dos exercícios da disciplina de Aprendizagem de Máquina, focados na criação, treinamento e ajuste fino (fine‑tuning) de redes neurais convolucionais (CNN) para classificação de imagens.

## Notebooks

* parte_1.ipynb: Construção da CNN básica. Define arquiteturas (sem e com data augmentation), configura funções de pré‑processamento e ImageDataGenerator, compila o modelo e prepara os conjuntos de treino e validação.
* parte_2.ipynb: Pipeline clássico de ML sobre imagens. Extrai features HOG e estatísticas (skew, kurtosis), monta pipelines com LogisticRegression, SVC e RandomForest, aplica GridSearchCV para ajuste de hiperparâmetros e exibe acurácias e matrizes de confusão.
* parte_3.ipynb: Fine‑tuning de ResNet50 pré‑treinada na ImageNet. Congela camadas iniciais, treina apenas a cabeça de classificação (transfer learning) e depois refina as últimas camadas com learning rate reduzido.
* parte_4.ipynb: Análise e visualização de resultados. Carrega modelos salvos, plota curvas de loss/accuracy, apresenta matriz de confusão consolidada e gera relatório de métricas (precision, recall, F1).

