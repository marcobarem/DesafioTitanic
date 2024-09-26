# Projeto de Classificação de Sobreviventes - Titanic

Este projeto realiza a análise e classificação dos passageiros do Titanic, utilizando diversos modelos de machine learning para prever se um passageiro sobreviveu ou não, com base em características como classe, sexo, idade e tarifa paga.

## Estrutura do Projeto

- `train.csv`: Arquivo contendo os dados de treino com as informações dos passageiros e se eles sobreviveram.
- `test.csv`: Arquivo contendo os dados de teste com as informações dos passageiros, sem a coluna de sobreviventes.
- `gender_submission.csv`: Arquivo contendo a submissão esperada (rótulos de sobrevivência) para os dados de teste.
- `main.py`: Arquivo principal contendo o código de processamento dos dados, treinamento de modelos e avaliação.

## Dependências

Este projeto requer a instalação das seguintes bibliotecas:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```