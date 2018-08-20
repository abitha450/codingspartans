# Play Hangman with a Neural Network model
A new neural network structure is designed in TensorFlow for playing the hangman game. The model is trained with 250,000 words dictionary and it achieves ~84% accuracy with guess limit 11.


# Playing Hangman with the Neural Network model
![Image of Hangman](https://github.com/lingbozhang/Hangman/blob/master/image/hangman.jpg)

A new neural network structure is designed for playing the hangman game. The net is trained with 250,000 words dictionary and the model achieves ~84% accuracy with guess limit 11.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 
### Prerequisites
Python;
TensorFlow;
Pandas;
numpy;
jupyter notebook;
## Running the tests
### How to train the model 
The hangman.py file contains the neural network model for the Hangman game. To train the neural network model, please download all files (including the hangman_model (pretrained weights and biases for the model), hangman.py and words_250000_train.txt (the trainning set) ). Then go to the directory where all files locate and run following command in your command line tool:

```
$ python3 hangman.py
```
Please note that the hangman.py will automatically save trained weights and biases for every 10 training epochs and it will take hours (~48 hours varied with different macine power) to get the optimal model (please contact the author: lingboz2015@gmail.com for the hangman.py file)
### How to test the model
To test the model, please run the hangman_test.ipynb file. First go to the directory where the hangman_test.ipynb file locates (in order to test the model, hangman_model directory and words_250000_train.txt are needed). Then run following comand in your command line tool to open the jupyter notebook:
```
$jupyter notebook hangman_test.ipynb
```
Run the jupyter notebook step by step and you will see the performance of the model .
## Author

* **Lingbo Zhang** 
:lingboz2015@gmail.com

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


