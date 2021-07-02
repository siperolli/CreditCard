Os notebooks consistem em apresentar comparações para resolver problemas de detecção de fraudes de cartões de crédito e como fazer o balanceamento de base desbalanceada. 

**Como detectar operações fraudulentas baseada no histórico de transações?**


**Metodologia aplicada:** 

- Tratamento de dados

- Comparação de algoritmos 

- PCA

- Balanceamento dos dados

- Gridsearchcv para definir os melhores hiperparâmetros do melhor algoritmo

**Conjundo de dados:**

Transações com cartões de crédito em dois dias de setembro de 2013 por titulares de cartões europeus

- Eventos: 284.807

- Recursos: 31 (V1,...,V28, Tempo, Valor, Classe)

- Fraudes: 0,172% 

- Linhas duplicadas: 1.081 (19 fraudes)

**Algoritmos usados:**

- Redes Neurais

- Random forest

- Regressão logística

- SVM

- XGBoost

- Árvore de Decisão

- Análise Discriminante Quadrática

**Avaliação do melhor algoritmo: Random Forest**

**Conclusão**

Este trabalho apresentou um estudo comparativo de 7 algoritmos de aprendizado supervisionado
Após aplicarmos o PCA não foi verificada alteração significativa na redução de dimensionalidade
O balanceamento foi feito usando SMOTE.
O melhor resultado foi encontrado no balanceamento somente no treinamento, pois dessa forma conseguimos manter os dados desbalanceados como no mundo real
O random forest mostrou-se o melhor algoritmo para predizer esse tipo de problema
Foi utilizado o gridsearchcv para definir os melhores hiperparâmetros no random forest

**Este trabalho foi apresentado a pós em conjunto com a Márcia Regina Ferreira Batista https://github.com/marciarbms/ProjetoFinal**

