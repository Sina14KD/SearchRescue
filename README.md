# Muitple UAVs Coverage Path Planning for Search and Rescue
This file includes the Python code for the NOPP algorithm proposed in the paper "An exact coverage path planning algorithm for UAV-based search
and rescue operations".

How to run the file:

1- install packages in requirements.txt

2- Run the nopp_algorithm.py

Example: 

n=15 (number of cells along the length of the rectangular area)

m=15 (number of cells along the width of the rectangular area)

q=4 (number of drones)

The solution was generated by the NOPP algorithm:

[[[1, 12], [1, 11], [1, 10], [1, 9], [1, 8], [1, 7], [1, 6], [1, 5], [1, 4], [1, 3], [1, 2], [1, 1], [2, 1], [2, 2], [2, 3], [2, 4], [2, 5], [2, 6], [2, 7], [2, 8], [2, 9], [2, 10], [2, 11], [2, 12], [3, 12], [3, 11], [3, 10], [3, 9], [3, 8], [3, 7], [3, 6], [3, 5], [3, 4], [3, 3], [3, 2], [3, 1], [4, 1], [4, 2], [4, 3], [4, 4], [4, 5], [4, 6], [5, 6], [5, 5], [5, 4], [5, 3], [5, 2], [5, 1], [6, 1], [7, 1], [8, 1], [9, 1], [10, 1], [11, 1], [12, 1], [13, 1], [14, 1], [15, 1]], [[1, 13], [2, 13], [3, 13], [4, 13], [4, 12], [4, 11], [4, 10], [4, 9], [4, 8], [4, 7], [5, 7], [5, 8], [5, 9], [5, 10], [5, 11], [5, 12], [5, 13], [6, 13], [6, 12], [6, 11], [6, 10], [6, 9], [6, 8], [6, 7], [6, 6], [6, 5], [6, 4], [6, 3], [6, 2], [7, 2], [7, 3], [7, 4], [7, 5], [7, 6], [8, 6], [8, 5], [8, 4], [8, 3], [8, 2], [9, 2], [10, 2], [11, 2], [12, 2], [13, 2], [14, 2], [15, 2], [15, 3], [15, 4], [15, 5], [15, 6], [15, 7], [15, 8], [15, 9], [15, 10], [15, 11], [15, 12], [15, 13]], [[1, 14], [2, 14], [3, 14], [4, 14], [5, 14], [6, 14], [7, 14], [7, 13], [7, 12], [7, 11], [7, 10], [7, 9], [7, 8], [7, 7], [8, 7], [8, 8], [8, 9], [8, 10], [8, 11], [8, 12], [8, 13], [8, 14], [9, 14], [9, 13], [9, 12], [9, 11], [9, 10], [9, 9], [9, 8], [9, 7], [9, 6], [9, 5], [9, 4], [9, 3], [10, 3], [10, 4], [10, 5], [10, 6], [11, 6], [11, 5], [11, 4], [11, 3], [12, 3], [13, 3], [14, 3], [14, 4], [14, 5], [14, 6], [14, 7], [14, 8], [14, 9], [14, 10], [14, 11], [14, 12], [14, 13], [14, 14], [15, 14]], [[1, 15], [2, 15], [3, 15], [4, 15], [5, 15], [6, 15], [7, 15], [8, 15], [9, 15], [10, 15], [10, 14], [10, 13], [10, 12], [10, 11], [10, 10], [10, 9], [10, 8], [10, 7], [11, 7], [11, 8], [11, 9], [11, 10], [11, 11], [11, 12], [11, 13], [11, 14], [11, 15], [12, 15], [12, 14], [12, 13], [12, 12], [12, 11], [12, 10], [12, 9], [12, 8], [12, 7], [12, 6], [12, 5], [12, 4], [13, 4], [13, 5], [13, 6], [13, 7], [13, 8], [13, 9], [13, 10], [13, 11], [13, 12], [13, 13], [13, 14], [13, 15], [14, 15], [15, 15]]]


