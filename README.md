# GPT for Generating New Shakespeare Text
This Jupyter notebook project uses Pytorch, Numpy, and Pandas to create a GPT model for generating new Shakespeare (or any author's) text from scratch.

## Installation
To run this notebook, you need to have the following libraries installed:

- Pytorch
- Numpy
- Pandas

## You can install these libraries using pip by running the following command:
```
bash
Copy code
!pip install torch numpy pandas 
```
## Dataset
This project uses a dataset of Shakespeare's plays, which can be downloaded from here. The dataset consists of a CSV file with columns for the play name, the act number, the scene number, and the text of the scene.

## Preprocessing
The dataset is preprocessed by tokenizing the text and creating a vocabulary of words used in the plays. The tokens are then converted to numerical values using the vocabulary.

## Model
The GPT model used in this project is a multi-layer transformer network, implemented in Pytorch. The model is trained on the preprocessed dataset using the Adam optimizer and the cross-entropy loss function.

## Generating New Text
Once the model is trained, it can be used to generate new Shakespeare text from scratch. The user can input a prompt, and the model will generate text starting from that prompt.

## Conclusion
This project demonstrates the use of Pytorch and numpy to create a GPT model for generating new Shakespeare text from scratch. The code can be adapted to other text datasets and used to generate new text in any style.
