
# FIAP - Faculdade de Informática e Administração Paulista 

<p align="center">
  <a href="https://www.fiap.com.br/">
    <img src="https://github.com/henriquehsilva/template-projeto-fiap/blob/main/assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width="40%" height="40%">
  </a>
</p>

---
# ML - Análise e Modelagem Preditiva de Produtos Agrícolas

### Descrição Geral do Projeto
Neste notebook, realizamos uma análise completa de um dataset de produtos agrícolas com o objetivo de entender as condições ideais para o cultivo de diferentes safras e desenvolver modelos preditivos para classificar a cultura com base nessas condições. As principais etapas realizadas foram:

Carga e Inspeção dos Dados: Iniciamos carregando o dataset produtos_agricolas.csv e realizando uma inspeção inicial para entender a estrutura dos dados, tipos de variáveis e identificar a presença de valores faltantes.

Limpeza dos Dados: Para lidar com os valores faltantes identificados, optamos por preencher os dados ausentes em cada coluna numérica com a média da respectiva coluna.

Análise Exploratória de Dados (EDA): Realizamos uma análise exploratória aprofundada com a criação de diversos gráficos, incluindo:

Histogramas para visualizar a distribuição de cada feature numérica.
Um gráfico de contagem para verificar a distribuição das diferentes culturas ('label').
Um pairplot para explorar as relações entre todas as features numéricas, diferenciando por cultura.
Gráficos de violino para visualizar a distribuição das features numéricas para cada cultura.
Boxplots para identificar outliers e a distribuição das features numéricas por cultura.
Uma matriz de correlação para entender a relação entre as features numéricas.
Identificação das Condições Ideais para as Culturas: Agrupamos os dados por cultura ('label') e calculamos estatísticas descritivas (média, mediana, desvio padrão, etc.) para as features numéricas. Isso nos permitiu ter uma ideia do "perfil ideal" de solo e clima associado a cada cultura presente no dataset.

Preparação dos Dados para Modelagem: Preparamos os dados para o treinamento dos modelos preditivos. Esta etapa incluiu:

Separar as features (variáveis independentes) da variável alvo ('label').
Codificar a variável alvo categórica ('label') em valores numéricos usando LabelEncoder.
Dividir o dataset em conjuntos de treinamento e teste para avaliar o desempenho dos modelos em dados não vistos.
Normalizar as features numéricas usando MinMaxScaler para garantir que todas as features tenham a mesma escala, o que é importante para o desempenho de alguns algoritmos.
Desenvolvimento e Avaliação de Modelos Preditivos: Treinamos 5 modelos de classificação diferentes para prever a cultura com base nas features de solo e clima:

K-Nearest Neighbors
Regressão Logística
Support Vector Machine
Decision Tree
Random Forest
Para cada modelo, calculamos a acurácia e geramos um relatório de classificação para avaliar métricas como precisão, recall e F1-score.

Avaliação Comparativa dos Modelos: Comparamos o desempenho dos 5 modelos treinados. Apresentamos as acurácias de cada modelo e visualizamos essa comparação em um gráfico de barras. Além disso, geramos as Curvas ROC (Macro-Average) para uma comparação visual mais aprofundada da capacidade de discriminação de cada modelo.

Com base na acurácia e nas Curvas ROC, o modelo Random Forest demonstrou ser o mais eficaz para a tarefa de classificação neste dataset.

## Time
<p align="left">
  <a href="https://github.com/agodoi" target="_blank">
    <img src="https://github.com/agodoi.png" width="64" height="64" alt="@agodoi" />
  </a>
  <a href="https://github.com/SabrinaOtoni" target="_blank">
    <img src="https://github.com/SabrinaOtoni.png" width="64" height="64" alt="@SabrinaOtoni" />
  </a>
  <a href="https://github.com/henriquehsilva" target="_blank">
    <img src="https://github.com/henriquehsilva.png" width="64" height="64" alt="@henriquehsilva" />
  </a>
  <a href="https://github.com/manoellaweiser-gif" target="_blank">
    <img src="https://github.com/manoellaweiser-gif.png" width="64" height="64" alt="@manoellaweiser-gif" />
  </a>
  <a href="https://github.com/JoaoMDPaiva" target="_blank">
    <img src="https://github.com/JoaoMDPaiva.png" width="64" height="64" alt="@JoaoMDPaiva" />
  </a>
  <a href="https://github.com/Luiz-Frederico" target="_blank">
    <img src="https://github.com/Luiz-Frederico.png" width="64" height="64" alt="@Luiz-Frederico" />
  </a>
  <a href="https://github.com/younmariana-create" target="_blank">
    <img src="https://github.com/younmariana-create.png" width="64" height="64" alt="@younmariana-create" />
  </a>
</p>

---

### 📹 Demonstração em Vídeo

Link para o vídeo de demonstração: [Ver VIDEO_LINK.txt](VIDEO_LINK.txt)

## Licença

Este projeto está licenciado sob a Licença Creative Commons Atribuição 4.0 Internacional. Para mais detalhes, consulte o arquivo [LICENSE](LICENSE).
