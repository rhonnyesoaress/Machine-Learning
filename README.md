# Classificação de tumores com dados radiômicos

Prova prática da disciplina de **Paradigmas de Aprendizagem de Máquina** (UFPB). O objetivo foi classificar um tumor como **maligno ou benigno** a partir de características radiômicas, que são medidas extraídas de imagens médicas.

## O que foi feito

- **Pré-processamento:** codificação dos rótulos (LabelEncoder) e normalização (MinMaxScaler).
- **Redução de dimensionalidade** com PCA, comparando os modelos com e sem PCA.
- **Classificação** com Árvore de Decisão e MLP, com validação cruzada.
- **Agrupamento** com K-Means e agrupamento hierárquico, avaliados pelo coeficiente de silhueta.
- **Avaliação** com F1-score, AUC-ROC e matriz de confusão.

## Arquivos

| Arquivo | Conteúdo |
|---|---|
| `Prova_2_ML.ipynb` | Notebook com todo o desenvolvimento (feito no Google Colab) |
| `prova_2_parad_int_art-2.pdf` | Enunciado da prova |

**Stack:** Python · scikit-learn · SciPy · Pandas · Matplotlib
