# Generating Text Using RNN
Throughout this project, we are implementing a deep learning algorithm that can grasp complex sentence patterns and predict the following words, thus, generating text for TV shows. Initially, we have designed a preprocessing algorithm that can iterate over significant texts and map words with their following ones. This point aims to create row data for the deep learning model to learn from, irrelevant to text subjects and details. The model type we are implementing is the [Recurrent Neural Network](https://en.wikipedia.org/wiki/Recurrent_neural_network). The first layer of the model represents an embedding layer, mapping words into vector representations using binary vectors and weights. The posterior layers compose [Long Short-Term Memory LSTM]([https://colah.github.io/posts/2015-08-Understanding-LSTMs/) layers to learn sequential data patterns. The model was built and trained, using PyTorch, on GPU, and achieved less than 3.5 [CrossEntropyLoss()](https://pytorch.org/docs/master/generated/torch.nn.CrossEntropyLoss.html).

Files in this repository:

- dlnd_tv_script_generation.ipynb  --- The notebook used to design and train the model.
- dlnd_tv_script_generation.html   --- An HTML version of the notebook.
- helper.py --- A Python script containing useful functions and classes for the project.
