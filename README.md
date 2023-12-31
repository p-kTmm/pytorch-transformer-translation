# pytorch-transformer-translation
I built a Transformer network from scratch for a translation task, following the structure described in the paper `Attention is All You Need`.
# Project Structure
`dataset.py` creates the PyTorch dataset. `model.py` is the file that contains the Transformer architecture. `train.py` file contains the training loop. 
# Dataset:
Our dataset is opus_books from HuggingFace, a dataset designed for translating from English to Italian.
# Training 
In order to train the model you must run the main.ipynb on GG Colab. File has hyperparameters of batch_size and num_epochs. You can change them as you like.
You can change dataset and the directory you want to save your model: tokenizer_file and model_folder.
# Inference
The main.ipynb file also supports inference with Beam Search. Please run the main.ipynb file on Google Colab to perform inference.
# Attention visualize
We also have a file named attention_visual.ipynb, which is used to plot and visually represent the relationships between words, showcasing how different words in a sentence are interconnected through attention mechanisms.
