
# AI Practicals⚙️





 ## All Practicals that are perform on Ubuntu Operating System - Jupyter Notebook

 ### Steps to Start the Jupyter notebook:

 1) Go to the Terminal

 2) type Jupyter Notebook

 3) It will run some stuff,after that it will open a page 

 4) first page = home page 

 5) to create a python file go to New -> Python3

 6) this is your ipynb (interactive python notebook file)

 7)  write code there!!

 ## 📂 Practicals




Each practical has a .txt file

 *  🔹 only code (to preserve security)
 *  🔹 commands (to understand code)
 *  🔹 proper identation



##
 ### 🛳 Practical 1: Travelling Salesman Problem(TSP)
 
 #### named as:  -[Practical1.txt](https://github.com/Atharvwavare/AI_practicals/blob/main/practical_1.txt)

#### implement Heuristic and Search Strategy

The Travelling Salesperson Problem (TSP) is a classic algorithmic problem in computer science and optimization. It asks:

"Given a list of cities and the distances between them, what is the shortest possible route that visits each city exactly once and returns to the starting city?"

Key Points:
 * It's a common example of a combinatorial optimization problem.

 * The goal is to minimize the total travel distance or cost.

 * TSP is NP-hard, meaning it’s difficult to solve quickly as the number of cities increases.

 * Used in route planning, logistics, manufacturing, and circuit design.

##

  ### 🛳 Practical 2 & 3: N-Queens Problem & Water Jug Problem 
#### Implement n-Queens problem using Hill-climbing / simulated annealing /A*algorithm 

### 2nd Practical
##
#### named as: --[practical_2a_queen.txt](https://github.com/Atharvwavare/AI_practicals/blob/main/practical_2a_queen.txt)

The N-Queens Problem is a classic puzzle in computer science and mathematics.

The goal is to place N queens on an N×N chessboard such that no two queens attack each other.

Rules:
 * A queen can move any number of squares vertically, horizontally, or diagonally.

  * No two queens should share the same row, column, or diagonal.


4-Queens Problem (N = 4)

. Q . .  
. . . Q  
Q . . .  
. . Q . 


### 3rd Practical
##
#### named as: --[practical_2b_jug.txt](https://github.com/Atharvwavare/AI_practicals/blob/main/practical_2b_jug.txt)

The Water Jug Problem is a classic problem in artificial intelligence and algorithm design. It's commonly used to teach search algorithms like Breadth-First Search (BFS) or Depth-First Search (DFS).

🧩 Definition:
Given two jugs with fixed capacities and an unlimited water supply, the goal is to measure a specific amount of water using only these two jugs — without any measuring marks on them.

🧪 Example Scenario:
You have:

Jug A (5 liters)

Jug B (3 liters)

Goal: Measure exactly 4 liters.

✅ Allowed Operations:
 * Fill a jug completely.

 * Empty a jug.

 * Pour water from one jug to another until:

 * the second jug is full, or the first jug is empty.


###

  ### 🛳 Practical 4: Sorting Algorithms
##
#### named as: --[practical_3.txt](https://github.com/Atharvwavare/AI_practicals/blob/main/practical_3.txt)

  #### Write a program for sorting algorithms using appropriate knowledge representation and reasoning techniques.  


A sorting algorithm is a method used to arrange data in order — like arranging numbers or words from smallest to largest (ascending) or largest to smallest (descending).

#### 1) Bubble Sort
Keep swapping neighbors if they’re in the wrong order. Do this many times.

🔍 How It Works:
 * Compare two neighbors.

 * Swap them if they are in the wrong order.

 * Repeat the process again and again until the list is sorted.

 #### 2) Selection Sort
Find the smallest and put it at the front. Repeat for all positions.

🔍 How It Works:
 * Find the smallest value in the list.

 * Swap it with the first position.

 * Then find the next smallest and swap with second position.

 * Repeat until sorted.




### 🛳 Practical 5: NLP tools
##
#### named as: --[practical_4.txt](https://github.com/Atharvwavare/AI_practicals/blob/main/practical_4.txt)

#### Write a program for the Information Retrieval System using appropriate NLP tools (such as NLTK, Open NLP, …) and perform following operations

1)  Text tokenization 
2)  Count word frequency 
3)  Remove stop words 
4)  POS tagging 


#### a. Text Tokenization
It breaks down text into smaller parts like words or sentences (called tokens).This is the first step in almost all NLP tasks.

Input: "I love Python." 

Output: ['I', 'love', 'Python', '.']

#### b. Count Word Frequency
It removes common words like "is", "the", "and" that don’t add much meaning.This makes the text cleaner for further processing.

Tokens: ['I', 'love', 'Python', 'love']

Output: {'I': 1, 'love': 2, 'Python': 1}

#### c. Remove Stop Words
It removes common words like "is", "the", "and" that don’t add much meaning.This makes the text cleaner for further processing.

Tokens: ['I', 'love', 'the', 'Python']

Output: ['love', 'Python']


#### d. POS Tagging (Part of Speech Tagging)
It labels each word with its grammatical role (noun, verb, adjective, etc.).Useful for understanding sentence structure and meaning.

Tokens: ['I', 'love', 'Python']

Output: [('I', 'PRP'), ('love', 'VBP'), ('Python', 'NNP')]




### 🛳 Practical 6: TIC TAC TOE game

##
#### named as: --[practical_5.txt](https://github.com/Atharvwavare/AI_practicals/blob/main/Practical_5.txt)

#### Write a program for the Tic-Tac-Toe game using the appropriate concepts from Game Theory 

Tic-Tac-Toe is a simple 2-player game played on a 3x3 grid.

 * One player is X, the other is O.

 * They take turns placing their symbol in an empty cell.

 * The goal is to get 3 of your symbols in a row — horizontally, vertically, or diagonally.


 X | O | X  
-----------
O | X |  O
-----------
O | O | X
-----------

where x Wins!!








