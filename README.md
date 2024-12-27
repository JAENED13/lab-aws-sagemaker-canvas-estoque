# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)
![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).

## Criando um modelo de estoque inteligente no SagerMaker Canvas.

Passo a passo:
1. Exportando e carregando o modelo dataseet no SELECT
2. Configurando o modelo no BUILD
3. Analisar os dados no ANALYSE
4. Fazer previsões de estoque tipo resuprimento, materiais consumo alto e baixo no PREDICT


## Fazendo a analise de estoque
Produto com maior saida de estoque _ Codigo 1015 - 2437 unidades seguido por código 1001 - 2423 unidades em 37 dias seguido cada.

MAE - (Mean Absolute Error) 0,002 indica que, em média, os valores previstos pelo modelo estão muito próximos dos valores reais.

R2 - (R-quadrado), ou Coeficiente de Determinação - R² de 100% (ou 1.0) indica que o modelo de regressão explica perfeitamente toda a variabilidade dos dados observados. Em outras palavras, todas as variações nos dados observados são explicadas pelo modelo, não deixando nenhuma variabilidade inexplicada.

RMSE - (Root Mean Square Error) de 0,004 indica que, em média, as previsões do modelo estão muito próximas dos valores reais, com uma diferença média de apenas 0,004 unidades.









