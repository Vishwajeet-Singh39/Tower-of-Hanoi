# Tower-of-Hanoi
Tower of Hanoi game


Note: You can exit the game at any time by pressing Ctrl+C


Goal:

Move all the elements from column A to column B or C without changing the order.


Rules:
*You can move top element.

*You cannot move more than one element at a time.

*You cannot place larger element on top of smaller element.

Instructions to play the game:
First you need to select the level by entering 1,2,3....upto 64(which will be practically impossible to solve as it will require (2^64)-1 moves.).

For Example you select level 2
You will see this

1

2

A    B    C

Next you will be asked to enter your move.
If you wish to move element from column A to Column B. Enter "1 2" where 1->A, 2->B, 3->C.
Output will be as shown:

2  1


A  B  C

By entering "1 2" you moved top element from column 1(A) to column 2(B).
Similarily you can move to column 3(C).

The solution will look like this

   1                    
   
   2                      
   
A  B  C   


OR


      1                    
   
      2                      
   
A  B  C 



After you completed the level you will be shown how many moves you made and Minimum no. of moves required to complete that level.
