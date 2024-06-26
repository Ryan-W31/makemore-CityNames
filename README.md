# makemore-CityNames

makemore-CityNames takes in a single .csv file filled with 20000+ US City Names from this [Kaggle dataset](https://www.kaggle.com/datasets/crawford/us-census-city-and-place-names/data) and uses machine learning models to predict new ones.

This repository was inspired by and follows along with Andrej Karpathy's [Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) youtube playlist.

Models implemented:

- [Bigram and Trigram](bigram.ipynb) - Character-Level Language Model 
- [Multi-Layer Perceptron (MLP)](mlp.ipynb) - Character-Level Language model
- [Recurrent Neural Network (RNN)](rnn.ipynb) - Character-Level Language model (kind of like WaveNet)

Other implementations:
- [Manual Backpropogation](citynames_manual_backprop.ipynb)