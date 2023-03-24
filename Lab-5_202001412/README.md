# $$\mathcal{\textcolor{darkgreen}{IT314-Software-Engineering-Lab 5}}$$



    Name: Zeel Bhanderi
    Student ID: 202001412
    Lab: 05

**Github tool and selected repository**


--> Here, i am using pylint tool for python

--> Repository that is used :
    https://github.com/TheAlgorithms/Python

Cloning and installing require tools

![cloning and installing](https://user-images.githubusercontent.com/75678316/227487902-9d18cb0a-69d0-4ac7-956b-b0714483a2b9.png)





**Performing static Analysis and error understanding**


(1) Code Analysed : https://github.com/TheAlgorithms/Python/blob/master/divide_and_conquer/mergesort.py

Tool Output:
![1st code](https://user-images.githubusercontent.com/75678316/227483738-d1f4ec0a-11a7-4323-9fb3-d4b134649b4a.png)


(2) Code Analysed : https://github.com/TheAlgorithms/Python/blob/master/divide_and_conquer/convex_hull.py

Tool Output:

![2nd code](https://user-images.githubusercontent.com/75678316/227484065-b9b6a08c-962e-491e-8145-0272f75a4f69.png)


(3) Code Analysed : https://github.com/TheAlgorithms/Python/blob/master/divide_and_conquer/inversions.py

Tool Output:

![3rd code](https://user-images.githubusercontent.com/75678316/227484693-9ffea8ef-9c93-4879-b4b0-d41c94bb1d9a.png)

(4) Code Analysed : https://github.com/TheAlgorithms/Python/blob/master/dynamic_programming/viterbi.py

Tool Output:

![4th code](https://user-images.githubusercontent.com/75678316/227485156-a6726598-5f2b-4c8f-a051-d4995dd22b6b.png)

(5) Code Analysed :  https://github.com/TheAlgorithms/Python/blob/master/dynamic_programming/rod_cutting.py

Tool Output:

![5th code](https://user-images.githubusercontent.com/75678316/227485393-d7278107-6658-4d87-9161-46cc58d450d9.png)

(6) Code Analysed :  https://github.com/TheAlgorithms/Python/blob/master/neural_network/convolution_neural_network.py

Tool Output:

![6th code](https://user-images.githubusercontent.com/75678316/227485692-227608ba-aa86-48a9-a32d-43eeeec523d0.png)



**Understanding Errors:**

        (1) C0114: Missing module docstring (missing-module-docstring)

        (2) C0103: Attribute name "x" doesn't conform to snake_case naming style (invalid-name)

        (3) R1705: Unnecessary "elif" after "return", remove the leading "el" from "elif" (no-else-return)
        
        (4) R1714: Consider merging these comparisons with "in" to 'k not in (i, j)' (consider-using-in)

        (5) R1702: Too many nested blocks (6/5) (too-many-nested-blocks)
        
        (6) C0116: Missing function or method docstring (missing-function-docstring)

        (7) R0914: Too many local variables (19/15) (too-many-locals)

        (8) R1720: Unnecessary "else" after "raise", remove the "else" and de-indent the code inside it (no-else-raise)
        
        (9) R0902: Too many instance attributes (14/7) (too-many-instance-attributes)
        
        (10) W0612: Unused variable 'data_focus1' (unused-variable)
        
        (11) W0105: String statement has no effect (pointless-string-statement)
