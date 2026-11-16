# Student Depression Detection

Projeto acadêmico desenvolvido para a disciplina de **Inteligência Artificial**, com o objetivo de aplicar técnicas de Machine Learning para identificar padrões associados à depressão em estudantes, utilizando o algoritmo **XGBoost** para classificação binária.

## Objetivo do projeto

Desenvolver um modelo de classificação capaz de identificar, com base em características demográficas, acadêmicas, familiares e sociais, se um estudante apresenta ou não indicação de depressão segundo os dados do dataset.

O problema foi estruturado como uma tarefa de classificação binária:

- `0`: Não apresenta depressão.
- `1`: Apresenta depressão.

## Dataset

Foi utilizado o [Student Depression Detection Dataset](https://www.kaggle.com/datasets/mkhoirulmustaqim/student-depression-detection-dataset), disponibilizado no Kaggle.

O conjunto de dados utilizado contém **4.464 registros e 13 variáveis originais**, incluindo:

| Variável | Descrição |
|---|---|
| Gender | Gênero do estudante |
| Age | Idade |
| Family_background | Condição socioeconômica familiar |
| Relationship_status | Situação do relacionamento |
| Marital_status | Estado civil |
| Living_style | Estilo de moradia |
| Current_semester | Semestre atual |
| CGPA | Média acadêmica acumulada |
| friend_circle | Indicador de círculo de amizades |
| Health_condition | Condição de saúde |
| Cost_without_study | Gastos sem considerar os estudos |
| Home_division | Região de residência |
| Depression | Variável-alvo |

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost

## Resultados

Na avaliação realizada sobre o conjunto de validação, o modelo apresentou os seguintes resultados:

| Métrica | Resultado |
|---|---:|
| Accuracy | 99% |
| Precision (classe 0) | 99% |
| Recall (classe 0) | 100% |
| F1-score (classe 0) | 99% |
| Precision (classe 1) | 99% |
| Recall (classe 1) | 97% |
| F1-score (classe 1) | 98% |

Os resultados indicam um alto desempenho na classificação dos registros do conjunto de validação.

**Aviso:** este projeto possui finalidade exclusivamente acadêmica e educacional.
