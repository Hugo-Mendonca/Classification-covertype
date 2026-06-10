# Inventário Florestal: Classificação de Cobertura com Machine Learning

Este projeto é um estudo acadêmico desenvolvido no curso de Sistemas de Informação da UFPE, focado na classificação multiespectral de cobertura florestal. O objetivo é investigar a eficácia de diferentes algoritmos de Machine Learning, comparando modelos clássicos com arquiteturas de *Ensemble* avançadas.

## 🎯 Objetivo
O desafio central consiste em lidar com dados de alta dimensionalidade e um severo desbalanceamento de classes. Através de uma abordagem de *Pipeline* rigorosa, buscamos identificar a arquitetura capaz de oferecer o melhor equilíbrio entre performance (F1-Score) e capacidade de generalização.

## 🧠 Metodologia
A pesquisa foi estruturada em seis etapas:
1. **Análise Exploratória:** Tratamento de ruído e análise de distribuições.
2. **Engenharia de Pipelines:** Testes com *undersampling* e *SMOTE*.
3. **Modelagem:** Comparação entre KNN, SVM, MLP e modelos de árvore.
4. **Ensembles:** Implementação de Random Forest, XGBoost, LightGBM e Stacking Heterogêneo.
5. **Avaliação:** Comparação de métricas (F1, ROC/PR Curves) para validar o modelo campeão.
6. **Conclusão:** Validação da eficácia do Stacking como ferramenta de meta-aprendizado.

## 📈 Resultados Preliminares
A arquitetura do **LightGBM**  superou os demais classificadores , alcançando um F1-Score de **0.93** na etapa final, provando ser a solução mais robusta para o inventário florestal.
