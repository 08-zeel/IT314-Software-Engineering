# Lab-5_202001181

**Software Engineering**

    Name: Zeel Bhanderi
    Student ID: 202001412
    Lab: 05

**Github tool and selected repositry**


Here, i am using pylint tool for python

https://github.com/TheAlgorithms/Python

![image](https://user-images.githubusercontent.com/83700057/225568552-f3f77595-e116-47b4-aa08-88ed2159cb90.png)


Cloing and installing require tools


**Performing static Analysis and error understanding**


(1) https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week6_dynamic_programming2/3_maximum_value_of_an_arithmetic_expression/placing_parentheses.py

Tool Output:
![image](https://user-images.githubusercontent.com/83700057/225569242-0e5c4a47-d744-420b-b578-350b68ef3c9e.png)

(2) https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week6_dynamic_programming2/1_maximum_amount_of_gold/knapsack.py

Tool Output:

![image](https://user-images.githubusercontent.com/83700057/225570057-bf8db995-b250-4538-a904-b682c2211600.png)

(3) https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week6_dynamic_programming2/2_partitioning_souvenirs/partition3.py

Tool Output:

![image](https://user-images.githubusercontent.com/83700057/225570809-91ee6530-5346-49e0-a6a4-0efd0b96cb46.png)

(4) https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week5_dynamic_programming1/4_longest_common_subsequence_of_two_sequences/lcs2.py

Tool Output:

![image](https://user-images.githubusercontent.com/83700057/225571548-9c6afada-36ec-439e-b552-2e05eb527f74.png)

(5) https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week5_dynamic_programming1/3_edit_distance/edit_distance.py

Tool Output:

![image](https://user-images.githubusercontent.com/83700057/225571891-61226b93-7411-4e7a-8d77-2b641848d4a1.png)




**Understanding Errors:**

        (1) C0303: Trailing whitespace (trailing-whitespace): Used when there is whitespace between the end of a line and the newline.

        (2) C0114/C0ll6: Missing module docstring/function docstring:   This indicates that neither the modules nor the functions have a docstring defined. The docstring functions as a kind of comment or text explanation that the compiler ignores but which aids in explaining the function's or module's intended use to others. Writing docstrings is a wise move.

        (3) W0622: Redefining built-in 'input' (redefined-builtin): Used when a built-in is overridden by a variable or method.

        (4) C0103:The variable doesn't match the snake_case naming style. The defined variable is not named using the snake_case convention, as indicated by this error.

        (5) W0621: Redifining name from outerscope: This mistake indicates that a global variable with the same name as a local variable. By doing this, the global version of the variable is hidden and the local scope is changed to use the local version of the variable.

        (6) C0305: Trailing newlines (trailing-newlines): This error tells that there are trailing blank lines in a file.

        (7) R1705: Unnecessary "else" after "return", remove the "else" and de-indent the code inside it (no-else-return): This occurs when an else line is added following a "return" statement that is never actually executed.

        (8) C0321: More than one statement on a single line: This error tells that there is an on statement are found on the same line.
