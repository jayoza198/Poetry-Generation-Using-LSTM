# Poetry-Generation-Using-LSTM

## Model Architecture

Embedding Layer: This layer converts words into dense vectors in a multidimensional space, allowing the model to work with continuous representations of words.

LSTM Layers: Multiple Long Short-Term Memory (LSTM) layers are stacked to capture intricate patterns and dependencies within the text data. LSTMs are particularly effective in handling sequences and preserving contextual information.

Batch Normalization: This step normalizes the activations in each layer, which aids in faster convergence during training and prevents overfitting, a common issue in machine learning models.

Dropout: Dropout is introduced to the model as a regularization technique to reduce overfitting by randomly disabling a fraction of neurons during training.

Dense Layers: Fully connected layers follow, responsible for outputting probabilities for the next word in the sequence.

Softmax Activation: The softmax activation function computes probabilities for each word in the model's vocabulary, allowing the model to choose the most likely next word based on these probabilities.

Model Training:

Loss Function: The loss function used in LSTM-based text generation is typically categorical cross-entropy. This loss function measures the difference between the predicted word distribution and the actual word distribution, encouraging the model to generate words that align with the training data.

Optimizer: The Adam optimizer is employed during training to minimize the loss. Adam is an optimization algorithm that efficiently adjusts the model's parameters, facilitating faster and more effective convergence.

Model Compilation: The model is compiled with the specified loss function, optimizer, and accuracy as the evaluation metric, enabling it to learn and improve its text generation capabilities over the course of training.


## Diagram

![image](https://github.com/jayoza198/Poetry-Generation-Using-LSTM/assets/71382456/2df1dede-92b9-4c12-a707-d44a8ccaf0fa)

