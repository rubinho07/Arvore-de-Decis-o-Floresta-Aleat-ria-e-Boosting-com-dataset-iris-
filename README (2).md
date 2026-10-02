# Classificação do Dataset Iris

Projeto desenvolvido para comparar diferentes modelos de classificação utilizando o dataset **Iris Species**.

## Objetivo

O objetivo é analisar qual modelo apresenta a melhor **acurácia** e **sensibilidade** na classificação das espécies de flores Iris.

## Modelos utilizados

- Support Vector Machine (SVM)
- Árvore de Decisão
- Floresta Aleatória
- Gradient Boosting

Os modelos foram executados com os parâmetros padrão e também com o **GridSearchCV**, utilizado para procurar as melhores combinações de parâmetros.

## Dataset

O dataset possui informações sobre três espécies:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

As características utilizadas foram o comprimento e a largura das sépalas e pétalas.

## Preparação dos dados

Os dados foram separados da seguinte maneira:

- 80% para treinamento
- 20% para teste

No modelo SVM, foi utilizado o `StandardScaler` para padronizar os dados por meio de um Pipeline.

## Resultados

O melhor resultado foi obtido pelo **SVM sem GridSearchCV**, com:

- Acurácia: **96,67%**
- Sensibilidade: **96,67%**

O Boosting sem GridSearchCV, a Floresta Aleatória com GridSearchCV e o Boosting com GridSearchCV também alcançaram 96,67% nas duas métricas.

## Tecnologias utilizadas

- Python
- Pandas
- Scikit-learn
- Kaggle Notebooks

## Arquivo do projeto

- `arvore-de-decis-o-floresta-aleat-ria-e-boosting.ipynb`

## Autor

Luis Fernando Rubinho Souza

Projeto desenvolvido para a disciplina de Inteligência Artificial.
