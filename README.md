# TicTacToeTeamNNN

Tic Tac Toe solver  

Trained the VGG16 model on the training images after augmenting them to increase the quantity of training images.
The input grid image is broken into 9 smaller images (of each grid) and then passed into the trained VGG16 model to classify whether X or O.
Further, the board state is passed to the minimax algorithm which predicts the probable winner from that position.  
The VGG16 based model can be found at [this link](https://drive.google.com/file/d/1LOoUyUGXGKcQv6VMpImxX-ZYRdgziirE/view?usp=sharing)

Created by Team Neural Network Nerds (NNN)  

Akshat Kasarwal  
Joel John Mathew  
Soham Mukherjee  
(Wing C4)  


However, due to some reason, I'm unable to run the file 'csv_file_generation.ipynb' on colab as it keeps crashing 'memory not sufficient'.


