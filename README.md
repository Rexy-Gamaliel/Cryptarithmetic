# Cryptarithmetic Solver

### Description
A cryptarithmetic equation solver using **brute force** algorithm implemented in python

### Requirement
* Python3 installed. Please refer to the internet for the installation ;)

### How to use
1. Clone this repository to your local directory by navigating to your local directory by typing this line in the command line:
    `git clone "https://github.com/Rexy-Gamaliel/Cryptarithmetic"`
2. Configure the equation you want to solve in a .txt file with the following format:
   ```
   WORDA
   WORDB
   WORDC
   ------
   RESULT
   ```
   Things to be noted:
   * Operands are to be inputted above the dash row, while a single result is to be inputted below it
   * You may input arbitrary number (> 1) of operands above the dash row
   * The number of dashes in the dash row is irrelevant
   * The equation would be intepreted as **summation** of the *operands* resulting in *result*
   * The input file is **case-sensitive**
   * The default file to be loaded to the program is `test1.txt`. If you wish to change the file to be loaded, you have to edit this line `with open("../test/test1.txt") as file:` in the program
3. Go to `/src` folder
4. Run the python program


#### Rexy Gamaliel R. 13519010
