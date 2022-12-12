# Natixis Datacamp 🏦

Central bank speeches often provide information on the economic health of countries, trends and the near future of the global economy. These same trends are usually linked to fluctuations in market volatility indexes. The aim of this work is to predict the evolution of the VIX and EURUSDV1M indices using speeches from the US and European central banks.
By using NLP models, decision trees and neural networks, we performed a regression task on the value of these indexes and a classification task on the bearish or bullish trend of these indices.


1. Data cleaning: strange tokens
2. Tokenization (if not using pertained models)
3. Encoder (pertained model) to get speech representation (1 sentence=1 vector or 1 paragraph=1 vector, a list of vector=1 speech with zero paddings) 
4. Feature Extractions 
5. Decoder to do the prediction task. (Input = speech vector representation, stock prices, other features)
6. Other technique details (how to represent missing speeches)


@Thomas Kessous, Xinyu Liu, Manan Gupta, François Schmerber, Wanqi Hong
