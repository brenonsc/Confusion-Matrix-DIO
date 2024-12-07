# Confusion-Matrix-DIO

Este repositório contém um exemplo de aplicação prática de visualização e análise de métricas de classificação usando uma matriz de confusão, projetado para ser executado no Google Colab. O código utiliza o dataset MNIST para treinar uma rede neural convolucional simples e avalia o desempenho do modelo com base em diversas métricas extraídas da matriz de confusão.  
<br>

## Funcionalidades

- **Treinamento de modelo CNN:** Rede neural convolucional para classificação de dígitos do MNIST.  
- **Geração de matriz de confusão:** Avalia as previsões do modelo em relação aos rótulos verdadeiros.  
- **Visualização da matriz de confusão:** Exibe uma matriz de confusão normalizada usando um heatmap do Seaborn.  
- **Cálculo de métricas de desempenho:** Inclui sensibilidade, especificidade, precisão, acurácia e F-score.  
- **Gráficos de métricas:** Visualização das métricas em forma de gráfico de barras.  
<br>

## Fluxo de Execução

1. **Carregar e pré-processar dados:**  
   O dataset MNIST é carregado, as imagens são redimensionadas e normalizadas para [0, 1].  

2. **Construir e treinar o modelo:**  
   Um modelo de rede neural convolucional (CNN) é definido, compilado e treinado em 5 épocas com o dataset MNIST.  

3. **Avaliar o modelo:**  
   Após o treinamento, as previsões do modelo são comparadas aos rótulos verdadeiros, e uma matriz de confusão é gerada.  

4. **Visualizar a matriz de confusão:**  
   A matriz de confusão normalizada é exibida como um heatmap, representando a relação entre rótulos verdadeiros e previstos.  

5. **Calcular métricas de desempenho:**  
   Métricas como sensibilidade, especificidade, precisão, acurácia e F-score são calculadas a partir da matriz de confusão.  

6. **Exibir métricas em gráfico de barras:**  
   Um gráfico de barras exibe os valores médios de cada métrica calculada.  
<br>

## Exemplo de Resultados

### Matriz de Confusão Normalizada  

O heatmap exibirá a matriz de confusão normalizada, indicando a precisão do modelo para cada classe:  
- Eixo Y: Rótulos verdadeiros  
- Eixo X: Rótulos previstos  

### Gráfico de Métricas  

Um gráfico de barras apresentará as métricas médias de desempenho:  
- **Sensitivity (Recall):** Proporção de verdadeiros positivos corretamente identificados.  
- **Specificity:** Proporção de verdadeiros negativos corretamente identificados.  
- **Precision:** Proporção de previsões positivas que são corretas.  
- **Accuracy:** Proporção geral de previsões corretas.  
- **F-Score:** Média harmônica de precisão e sensibilidade.
