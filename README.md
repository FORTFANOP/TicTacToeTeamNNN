# TicTacToeTeamNNN

Tic Tac Toe solver  

Trained the VGG16 model on the training images after augmenting them to increase the quantity of training images.
The input grid image is broken into 9 smaller images (of each grid) and then passed into the trained VGG16 model to classify whether X or O.
Further, the board state is passed to the minimax algorithm which predicts the probable winner from that position.  

Created by Team Neural Network Nerds (NNN)  

Akshat Kasarwal  
Joel John Mathew  
Soham Mukherjee  
(Wing C4)  

(The model doesn't predict correctly in some cases)  

However, due to some reason, I'm unable to run the file 'csv_file_generation.ipynb' on colab as it keeps crashing 'memory not sufficient'.


