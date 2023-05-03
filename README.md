# N-Queens-Variation

* In this problem. I created a matrix and placed M<N queens replacing on the matrix. We can change the matrix size and place Queens filling the all the matrix and calculate the permutations on the matrix. Therefore, we reach queen size less than needed from N queens and fill all the matrix with queens that not matching any queens on the chess board. It solves 500x500 in 2 minutes and 1000x1000 in 17 minutes.

* Methodology of the problem is that it fills the matrix with "2" values and look at the closest number that fill the matrix that is 0. After that it fills again the matrix with "2" and look and check if matrix has an 0 value. When all the zero values are filled with 1 and 2s the while loop terminates and less than N queen fills the chess board NxN.

* Choosen list shows the points and other variables are settled to minimize calculation time. First cell selected is randomly. Other cells are selected with brute force methodology. It is kind of NP problem and it solves very fastly the needed queens for the chess board.

* Link ==> https://colab.research.google.com/drive/1c61_QzrilW1AL0Ma1TyU5a2ZGrpsL0OC?usp=sharing
