# Tic-Tac-Toe-Game
Project Game on C language

Tic Tac Toe Game Development using C

While making a Tic Tac Toe game using C language, it is important to make use of arrays. The Xs and Os are kept in different arrays, and they are passed between several functions in the code to keep track of how the game goes. With the code here you can play the game choosing either X or O against the computer.

This Tic Tac Toe C game is such that you will have to input a numerical character, from 1 to 9, to select a position for X or O into the space you want. For example: if you are playing with O and you input 2, the O will go to first row – second column. If you want to place O in third row – first column, you have to enter 7. And, it is similar for the other positions.

This has been done this way because it is just a console application without graphics designed in C language. The gotoxy function has been used to print text in any part of the screen.

Function Used:
void menu() 
void go(int n)
void start_game()
void check_draw()
void draw_board()
void player_first()
void put_X_O(char ch, int pos)
void gotoxy (int x, int y)
![Screenshot](tik.jpg)
