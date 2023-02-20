# LipNet Implementation
Keras implementation of the method described in the paper 'LipNet: End-to-End Sentence-level Lipreading' by Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, and Nando de Freitas (https://arxiv.org/abs/1611.01599).

## Dataset
This model uses GRID corpus (http://spandh.dcs.shef.ac.uk/gridcorpus/)

### Get Started
To run the .ipynb locally:
1. Clone this repository
    ```
    git clone https://github.com/notkushagra/LipNet
    ```
2. Create a new environment.
3. ```source activate myenv```
4. ```pip install -r requirements.txt```
5. ```jupyter notebook```
6. Navigate to the repository folder and run the ```LipNet.ipynb```


## Pre-trained weights
For those of you who are having difficulties in training the model (or just want to see the end results), you can download and use the weights provided here: https://github.com/rizkiarm/LipNet/tree/master/evaluation/models. 

More detail on saving and loading weights can be found in [Keras FAQ](https://keras.io/getting-started/faq/#how-can-i-save-a-keras-model).


### References
* [LipNet Code](https://github.com/rizkiarm/LipNet/blob/master/README.md)
* Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, Nando de Freitas, “ LipNet: End-To-End Sentence-Level Lip-reading”. [Read link](https://arxiv.org/abs/1611.01599)
* Amit Garg, Jonathan Noyola, Sameep Bagadia, 2017 “Lip reading using CNN and and LSTM ”  [Read link](http://cs231n.stanford.edu/reports/2017/pdfs/227.pdf)
