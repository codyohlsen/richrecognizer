# "Rich Recognizer!!!"
Final Project for CSE 528 Computational Neuroscience: sound classification using neural networks.
Check back for updates!

## libraries required (python 3.5.x)
- `pip install numpy`
- `pip install matplotlib`
- `pip install librosa`
- `pip install tensorflow`
- `pip install pyaudio`
- `pip install wave`

## Python apps
- `rich_data_collector.py` - This program prompts you to say 'rich' or something else, and builds up the training data for the rich recognizer by tokenizing your words and saving them to separate .wav files.
- `learner.py` - This program learns from the data generated by the rich data collector using a Neural Network. It saves some of the data to test its predictions, and outputs a graph showing how well it was able to predict on the train and test data as we make more training epochs in the neural network. Finally, it asks for input files via the prompt and attempts to predict.
