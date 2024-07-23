# Deep_Learning_CNN_sentence_classification

![CNN-architecture-for-short-document-classification-taken-from-Zhang-and-Wallace-2015](https://user-images.githubusercontent.com/76741091/149726304-5fd25b68-1efd-47e9-81e2-1edb5260ed31.png)

# Deep_Learning_CNN_sentence_classification

In our experiment, fastText demonstrates superior performance compared to other models. The code can be found in `cnn_sentence_classification.ipynb`. Our findings closely align with those reported in Kim’s paper.

Since the original implementation by the authors was in PyTorch, transitioning from TensorFlow involved a learning curve. However, we successfully adapted and leveraged unsupervised pre-training of word vectors to enhance overall model performance.

Our study involves convolutional neural networks (CNNs) trained on pre-trained word vectors for sentence-level classification tasks. We demonstrate that a straightforward CNN with minimal hyperparameter tuning and static vectors achieves outstanding results across various benchmarks. Fine-tuning task-specific vectors further enhances performance. Additionally, we propose a simple architecture modification enabling the utilization of both task-specific and static vectors. Our CNN model is built and trained using PyTorch. Our results underscore the significance of unsupervised pre-training of word vectors in deep learning applications for natural language processing (NLP).

# Screenshots-

![image](https://user-images.githubusercontent.com/76741091/159180170-25350702-10dd-4a5a-81c8-6c0d6e601780.png)
![image](https://user-images.githubusercontent.com/76741091/159180376-3059550b-4812-48e1-a791-e46392acd6b5.png)
![image](https://user-images.githubusercontent.com/76741091/159180444-b6b0f400-a223-4be2-8b51-1bcfb3bf6323.png)
![image](https://user-images.githubusercontent.com/76741091/159181062-6a38ccb7-d287-4e8c-a37e-f60821f95808.png)
