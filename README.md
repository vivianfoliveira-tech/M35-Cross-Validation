# Cross Validation

Projeto de classificação binária que implementa um pipeline reprodutível para pré-processamento e modelagem: seleciona variáveis numéricas, aplica StandardScaler e treina um classificador linear (LogisticRegression) dentro de um esquema de validação estratificada (Stratified K-Fold) para garantir avaliação robusta entre folds. O repositório inclui o notebook com as etapas de limpeza básica, engenharia/seleção de atributos, definição do pipeline, avaliação com múltiplas métricas e scripts para reproduzir os resultados localmente (com instruções sobre dependências e execução). 

O foco do projeto é demonstrar um fluxo simples e auditável para validação de modelos, com atenção à reprodutibilidade e à detecção de potenciais fontes de data leakage antes de considerar o modelo para produção.
