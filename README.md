# CHESS:Predict_with_depth

Game of thrones and endings don’t sit that well together.But what if we give you a chance to decide the conclusion to a game of kings and queens!

## Challenge
The positions of white king and rook are plotted against black King and you have to predict either the number of moves it takes for the white king to win or say if the white king loses.

## Dataset
A KRK dataset was first described in 1977. This dataset is also a KRK dataset, meaning it consists of positions of White King, White Rook, and Black King. In such a scenario if both teams play optimally(Black moves first) the only possible outcomes are either a draw or White King wins. The attributes are :

White King file (column)

White King rank (row)

White Rook file

White Rook rank

Black King file

Black King rank

optimal depth-of-win for White in 0 to 16 moves, otherwise draw(-1) .

For simplification, positions have been stored in csv file. The train.csv has 7 columns, the last column is the number of moves required to win which is -1 in case of a draw and otherwise between 1-16 the rest 6 columns contain the position of White King and Rook and Black King.

## Evaluation Criteria
During evaluation Mean Absolute Error and F1 score will be used to test the efficiency of the model.

## LeaderBoard
https://www.aicrowd.com/challenges/aicrowd-blitz-2/problems/chess/submissions
