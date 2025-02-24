# 🍷 Projeto de Classificação de Vinhos  

## Objetivo  
Este projeto tem como objetivo construir um modelo de Machine Learning capaz de classificar vinhos com base em suas características físico-químicas. Utilizamos técnicas de aprendizado supervisionado e otimização de hiperparâmetros com `GridSearchCV`, buscando encontrar os melhores parâmetros para maximizar o desempenho do modelo.  

## Fluxo do Projeto  

### 🔹 1. Pré-processamento dos Dados  
- Carregamento e análise exploratória dos dados  
- Normalização e tratamento de valores ausentes  
- Separação dos conjuntos de treino e teste  

### 🔹 2. Treinamento do Modelo  
- Teste de diferentes algoritmos e seleção do melhor com `GridSearchCV`  
- Avaliação do desempenho utilizando métricas como **Acurácia, Precisão, Recall e F1-score**  
- Aplicação de validação cruzada com K-Fold para garantir a robustez do modelo  

### 🔹 3. Avaliação do Modelo  
- Impressão dos melhores hiperparâmetros encontrados  
- Análise do desempenho nos conjuntos de treino e teste  
- Comparação das métricas de desempenho ao longo dos folds da validação cruzada  

### 🔹 4. Interpretação dos Resultados  
- Exibição dos melhores hiperparâmetros e métricas médias  
- Geração de gráficos para facilitar a interpretação das métricas ao longo dos folds  
- Cálculo de métricas no conjunto de teste para avaliação final  

### 🔹 5. Análise da Importância dos Atributos  
- Extração dos coeficientes do modelo para identificar quais atributos mais influenciam a classificação do vinho  
- Geração de um gráfico de barras horizontais para visualização da importância dos atributos  

## Saída do Modelo  
- 📑 **Tabela de métricas por iteração do K-Fold**  
- 📈 **Estatísticas finais das métricas no conjunto de teste**  
- ✅ **Avaliação qualitativa da performance do modelo**  
- 📊 **Gráfico de importância dos atributos**  

Este projeto permite compreender quais fatores mais impactam a classificação dos vinhos e fornece uma solução robusta para análise preditiva, podendo ser aplicado para suporte na avaliação da qualidade dos vinhos em diferentes contextos.  

---

 **Quer contribuir?**  
Sinta-se à vontade para abrir uma issue ou um pull request! 🚀  
