# Análise de Dados de Propriedades em São Paulo

Este é um projeto de análise de dados de propriedades na cidade de São Paulo. O objetivo deste projeto é explorar e analisar um conjunto de dados contendo informações sobre propriedades, como preço, tamanho, número de quartos, localização, entre outros atributos. Além disso, o projeto envolve a aplicação de técnicas de pré-processamento, feature engineering, treinamento de modelos de regressão e avaliação de desempenho.

## Conteúdo

1. [Introdução](#introdução)
2. [Pré-processamento](#pré-processamento)
3. [Análise Exploratória de Dados](#análise-exploratória-de-dados)
4. [Feature Engineering](#feature-engineering)
5. [Modelagem](#modelagem)
6. [Avaliação e Visualização](#avaliação-e-visualização)
7. [Aplicação do Modelo](#aplicação-do-modelo)
8. [Conclusão](#conclusão)

## Introdução

Neste projeto, exploramos um conjunto de dados que contém informações sobre propriedades em São Paulo. O objetivo é realizar análises para entender as relações entre diferentes atributos e o preço das propriedades, bem como desenvolver um modelo de regressão para prever o preço com base em características das propriedades.

## Pré-processamento

O pré-processamento dos dados envolveu tratamento de valores ausentes, detecção e tratamento de outliers, bem como codificação de variáveis categóricas usando a técnica de one-hot encoding.

## Análise Exploratória de Dados

Realizamos uma análise exploratória de dados para compreender a distribuição das variáveis, identificar padrões e visualizar relações entre diferentes atributos. Gráficos de dispersão, histogramas e box plots foram utilizados para essa finalidade.

## Feature Engineering

Criamos novas features a partir dos dados originais, como a relação entre área e número de cômodos, e uma coluna fictícia para representar a proximidade de serviços públicos.

## Modelagem

Testamos vários modelos de regressão, incluindo Regressão Linear, Ridge, Lasso, Árvore de Decisão, Random Forest e Gradient Boosting. Avaliamos o desempenho de cada modelo usando métricas como MAE, MSE e R2.

## Avaliação e Visualização

Realizamos uma avaliação final do modelo escolhido usando dados de teste e comparamos suas métricas de desempenho com os modelos anteriores. Criamos gráficos para visualizar as previsões do modelo em comparação com os preços reais.

## Aplicação do Modelo

Finalmente, aplicamos o modelo escolhido para fazer previsões em novos dados de teste. Aplicamos as mesmas transformações de pré-processamento e feature engineering nos novos dados antes de fazer as previsões.

## Conclusão

Neste projeto, realizamos uma análise completa de dados de propriedades em São Paulo, desde o pré-processamento até a aplicação do modelo final. Foram exploradas diversas etapas, incluindo visualizações, engenharia de features e avaliação de desempenho de modelos de regressão. O modelo final mostrou um bom desempenho na previsão de preços das propriedades com base em suas características.

