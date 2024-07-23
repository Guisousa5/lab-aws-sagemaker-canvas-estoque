# Previsão de Estoque Inteligente na AWS com SageMaker Canvas

Este projeto visa a criação de um modelo inteligente para previsão de estoque utilizando o SageMaker Canvas da AWS. O projeto está organizado em módulos para facilitar a compreensão e execução. Abaixo, você encontrará uma descrição dos módulos e exemplos de código para cada etapa.

## Módulos do Projeto

1. **Introdução ao Projeto e ao SageMaker Canvas**
   - Neste módulo, será apresentada a proposta do projeto e introduzidos os conceitos fundamentais do SageMaker Canvas.

2. **Preparação dos Dados**
   - Prepararemos os dados para o treinamento do modelo. Isso inclui o carregamento, limpeza e formatação dos dados de estoque para uso no SageMaker Canvas.

   '''python
   import pandas as pd

   # Carregar os dados de estoque
   data = pd.read_csv('estoque.csv')

   # Realizar a limpeza dos dados (remover valores nulos, outliers, etc.)
   data_cleaned = data.dropna()'''
   
### 3. Preparação dos Dados
