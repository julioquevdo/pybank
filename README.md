# Previsão de Renda Utilizando Machine Learning

## Visão Geral

Este projeto foi desenvolvido como parte de uma simulação prática, onde o objetivo era resolver um problema empresarial utilizando ciência de dados e machine learning. O desafio era prever a renda anual de indivíduos com base em dados demográficos e laborais, permitindo uma segmentação mais eficiente e precisa de clientes.

## Contexto do Projeto

A situação proposta envolvia um banco fictício que enfrentava dificuldades por não possuir informações completas sobre a renda de seus clientes. Para solucionar esse problema, utilizamos um dataset público para desenvolver um modelo preditivo que auxilia na identificação de clientes elegíveis para uma oferta específica de produto financeiro.

## Objetivo

Criar um modelo de machine learning capaz de prever a renda anual de clientes com alta acurácia, utilizando dados como idade, gênero, profissão, horas trabalhadas por semana, entre outros. O modelo deveria ser eficiente o suficiente para ser implementado em escala real.

## Dados

- **Fonte do Dataset**: "Adult Income" (dados públicos).
- **Tamanho**: 48.842 instâncias e 15 variáveis.
- **Características utilizadas**:
  - Idade
  - Classe trabalhadora
  - Grau de educação
  - Estado civil
  - Profissão
  - Raça
  - Gênero
  - Horas trabalhadas por semana
  - Status de nativo do país
- **Classes**:
  - <=50K (renda anual menor ou igual a 50 mil)
  - >50K (renda anual maior que 50 mil)

## Metodologia

1. **Limpeza e Pré-processamento de Dados**:
   - Tratamento de valores faltantes e duplicados.
   - Codificação de variáveis categóricas.
   - Balanceamento das classes para evitar viés.

2. **Modelos Aplicados**:
   - Random Forest
   - Deep Learning (Rede Neural)

3. **Ajuste de Hiperparâmetros**:
   - Grid Search e Random Search.

4. **Avaliação**:
   - Divisão dos dados em treino e teste.
   - Uso de métricas como acurácia, recall e F1-score.

## Resultados

- **Acurácia do modelo**: 82%
- **Recall**: 89%
- **F1-score**: 83,5%
- **Impacto**:
  - Redução no tempo de trabalho do time de marketing.
  - Economia de recursos financeiros.

## Tecnologias Utilizadas

- Python
- Scikit-learn
- TensorFlow/Keras
- Pandas
- Matplotlib/Seaborn
- Grid Search e Random Search

## Aprendizados e Impacto

Este projeto reforçou a importância de:
- Um pipeline de dados bem estruturado para garantir a qualidade do modelo.
- Ajustes de hiperparâmetros para maximizar a performance.
- Colaboração em grupo para resolução de problemas complexos.
