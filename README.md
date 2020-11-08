# GameOfLife-Datasets-SB-Unit3_5_2

The project "Conway's Reverse Game of Life 2020" is a 
competition at Kaggle.com.  The training and test datasets for this 
project were retrieved from Kaggle.com.

The training dataset, i.e. TrainDataset-10Samples.csv, only contains 
10 samples - the original file contains 50000 samples.  I did not upload 
this file to the github project due to its size of 122MB.

The test dataset, i.e. TestDataset-10Samples.csv only contains 
10 samples - the original file contains 50000 samples.  I did not upload 
this file to the github project due to its size of 61MB.

In the training dataset, each sample contains 1252 columns.  These columns 
contain the 'ID' for the sample, 'Delta' for the sample (which is 
the number of steps you need to apply to get from the original 
cell configuration (which is the next 625 columns) to the ending configuration (which 
is the next 625 columns).

In the test dataset, each sample contains 627 columns.  These columns 
contain the 'ID' for the sample, 'Delta' for the sample, and the end 
cell configuration (which is the next 625 columns).  The training dataset and 
the test dataset differ in that the test dataset does NOT contain the 625 columns 
for the initial cell configuration (computing these 625 cell configuration is 
the goal of this project).

Here is some information from Kaggle.com on this "Game of Life"

The grid size is larger (25 vs. 25) and the grid wraps around from top to bottom and left to right
Submissions are solved forward by the appropriate number of steps, so that any correct starting solution will achieve a maximum score. This article contains the stepping function that is used for this competition.
Obligatory Disclaimer: A lot has changed since the original competition was launched 6 years ago. With the change from "exact starting point" to "any correct starting point", it is possible to get a perfect score. We just don't know how difficult that will be. Use it as a fun learning experience, and don't spoil it for others by posting perfect solutions!

~~~~~~~~~

The Game of Life is a cellular automaton created by mathematician John Conway in 1970. The game consists of a board of cells that are either on or off. One creates an initial configuration of these on/off states and observes how it evolves. There are four simple rules to determine the next state of the game board, given the current state:

Overpopulation: if a living cell is surrounded by more than three living cells, it dies.
Stasis: if a living cell is surrounded by two or three living cells, it survives.
Underpopulation: if a living cell is surrounded by fewer than two living cells, it dies.
Reproduction: if a dead cell is surrounded by exactly three cells, it becomes a live cell.


