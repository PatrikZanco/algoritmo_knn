# Análise de Dados do Dataset de Doenças Cardíacas
Descrição do Projeto
Este projeto envolve a análise exploratória e modelagem preditiva do dataset heart.csv, que contém informações médicas relacionadas a doenças cardíacas. O objetivo é identificar padrões e prever a ocorrência de doenças cardíacas em indivíduos com base em várias características médicas.

Estrutura do Dataset
O dataset inclui as seguintes colunas:

Idade (Age)
Sexo (Sex)
Tipo de Dor no Peito (ChestPainType)
Pressão Arterial em Repouso (RestingBP)
Colesterol (Cholesterol)
Nível de Glicose em Jejum (FastingBS)
Resultados Eletrocardiográficos em Repouso (RestingECG)
Frequência Cardíaca Máxima Alcançada (MaxHR)
Angina Induzida por Exercício (ExerciseAngina)
Depressão de ST induzida por exercício em relação ao repouso (Oldpeak)
Inclinação do Segmento ST do Exercício (ST_Slope)
Presença de Doença Cardíaca (HeartDisease)
Limpeza e Pré-processamento
Realizamos a limpeza dos dados, tratando valores ausentes e zeros em colunas críticas como 'Cholesterol' e 'RestingBP'. Também foi aplicado o escalonamento dos dados para normalização antes da modelagem.

Análise Exploratória
A análise inclui a visualização da distribuição de variáveis chave, a relação entre diferentes características e a prevalência da doença cardíaca. Utilizamos gráficos como histogramas, gráficos de barras e gráficos de dispersão para visualizar as tendências nos dados.

Modelagem Preditiva
Utilizamos o algoritmo K-Nearest Neighbors (KNN) para desenvolver um modelo capaz de prever a presença de doença cardíaca. O modelo foi avaliado usando a precisão e a matriz de confusão, e validado através da técnica de validação cruzada para garantir a robustez dos resultados.

Resultados
Os resultados mostram que o modelo alcançou uma acurácia satisfatória, sugerindo que as variáveis selecionadas são indicativas da presença de doenças cardíacas. Detalhes adicionais sobre a performance do modelo e insights específicos das análises podem ser encontrados nas seções subsequentes deste relatório.
