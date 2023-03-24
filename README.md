# Detecção de fraude
Palavras-chave: **ProfileReport, encoding, métricas de avaliação de modelos, Curva Roc, balanceamento de dados, decisionTreeClassifier, randomForestClassifier, regressão logística.**

## Sobre o projeto 
O objetivo deste projeto é desenvolver um modelo de Machine Learning capaz de identificar transações fraudulentas em um conjunto de dados histórico. A detecção de fraudes em transações é de grande importância para empresas de cartões de crédito e instituições financeiras, pois ajuda a evitar perdas financeiras e a proteger os clientes de atividades fraudulentas.  

Nós vamos usar uma base de dados do Kaggle chamada [Fraud Detection Example](https://www.kaggle.com/gopalmahadevan/fraud-detection-example) e ela tem uma fração de dados do [PaySim](https://github.com/EdgarLopezPhD/PaySim), um simulador de dados financeiros feito exatamente para detecção de fraude.  

Neste projeto foi seguido uma pipeline de machine learning, foi feito a coleta de dados, pegamos esses dados no kaggle e entendemos o que eles continham. Passamos para a análise exploratória com Pandas e Pandas Profiling, aplicamos um encoding nos dados e fizemos parte do balanceamento de dados neles.

Os dados precisavam ser balanceados para que conseguíssemos fazer o modelo de machine learning que alcançasse uma boa previsão, com mais dados de uma classe e menos de outra, não conseguiríamos um resultado tão bom.

Após termos feito toda a parte das análises e manipulações do banco de dados, conseguimos aplicar os três modelos de machine learning e compará-los. Então, fizemos a Regressão logística, a Árvore de decisão e a Floresta aleatória. Além disso, comparamos as três com várias métricas de avaliação de modelos e, ao final, foi utilizado tecnicas de aprimoramento no Random Forest.


## Autor 
Paulo César Souza Rubim filho 

https://www.linkedin.com/in/paulorubimf/
