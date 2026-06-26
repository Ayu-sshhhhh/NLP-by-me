# NLP
This repo contains some of the experiments conducted by me while learning Natural Language Processing (with a hint of Natural Language Understanding)

## What does it Do ?
- INPUT_TEXT(s) - Target texts/sequences you would like to discover patterns in
- INPUT_LAYER - Takes in target sequence
- TEXT_VECTORIZATION_LAYER - Maps input sequences to numbers
- EMBEDDING - Turns mapping of texts vectors to embedding matrix
- RNN_CELL(s) - Finds patterns in sequences
- HIDDEN_ACTIVATION - Adds non-linearity to learned features (non-straight lines)
- POOLING_LAYER - Reduces the dimensionality of learned sequence features (usually for Conv1D models)
- FULLY_CONNECTED_LAYER - Further refines learned features from recurrent layers
- OUTPUT_LAYER - Takes learned features and outputs them in shape of target labels
- OUTPUT_ACTIVATION - Adds non-linearities to output layer
