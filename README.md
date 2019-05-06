# 530 final project

Run Main.ipynb and follow the instructions there.

(be sure to download all .py files in this repository and upload to a place accessible by Main.ipynb)


# Extensions

### 1. Hidden Size
In order to change the hidden size of the model, we can call the following command in terminal 
```sh
!python train.py --hidden_size='size of your choice' --model_path='saved_models'
```
You also need to manually modify the hidden size parameter in model.py to match your input hidde size.

### 2. Pretrained model choice
To use a Resnet as pretrained model, download model_resnet.py, rename it to model.py and use it inplace of the original model.py.

### 3. Type of Recurrent Neural Network
To use GRU instead of LSTM, go to the decoder class in model.py and change the 'LSTM' (case matters), which only appears once, to 'GRU'.

# Evaluation and Output

To obtain the results in output.md, follow the instructions in Main.ipynb for evaluation.
