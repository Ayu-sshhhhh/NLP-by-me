# NLP
This repo contains some of the experiments conducted by me while learning Natural Language Processing (with a hint of Natural Language Understanding)

## What does it Do ?
- *INPUT_TEXT(s)* - Target texts/sequences you would like to discover patterns in
- *INPUT_LAYER* - Takes in target sequence
- *TEXT_VECTORIZATION_LAYER* - Maps input sequences to numbers
- *EMBEDDING* - Turns mapping of texts vectors to embedding matrix, *for ex. **king-man+woman = queen***
- *RNN_CELL(s)* - Finds patterns in sequences
- *HIDDEN_ACTIVATION* - Adds non-linearity to learned features (non-straight lines)
- *POOLING_LAYER* - Reduces the dimensionality of learned sequence features (usually for Conv1D models)
- *FULLY_CONNECTED_LAYER* - Further refines learned features from recurrent layers
- *OUTPUT_LAYER* - Takes learned features and outputs them in shape of target labels
- *OUTPUT_ACTIVATION* - Adds non-linearities to output layer

## Different types of Models trained :
- **Model 0** : Naive Bayes (baseline)
- **Model 1** : Feed-forward NN (dense model)
- **Model 2** : LSTM model
- **Model 3** : GRU model
- **Model 4** : Bidirectional-LSTM model
- **Model 5** : 1D Conv NN
- **Model 6** : TFHub pre-trained feature extractor
- **Model 7** : Same as model 6 with 10 % of training data
