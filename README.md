# Algo

## **Algorithm**
- Algorithm is a sequence of step by step to solve a particular problem


## **Different Approaches to Develop Algorithm**
  - **Greedy**
  - **Divide & Conquer**
  - **Dynamic Programming**
  - **Backtracking**
  - **Randomized Algorithm**

- **Greedy Method**
  - In the Greedy approach, at each step, a decision is  made to choose the local optimum without thinking about the future consequences
  - Example - Fractional Knapsack, Activity selection


- **Divide & Conquer**
  - Divide & Conquer Strategy involves dividing the problem into sub-Problems, recursively solving them and then recombining them for final answer
  - Example - Merge-Sort, Quick-Sort

- **Dynamic Programming**
  - The approach of the Dynamic Programming is similar to Divide & Conquer, difference is that whenever we have recursive function calls with same result, instead of calling them again, we try to store the result in data structure in the form of a table and retrieve the result from the table 
  
  - Thus overall time complexity is reduced
  
  - **Dynamic** means we dynamically decide whether to call a function or retrieve values from the table
  
  - Example - 0-1 Knapsack, Fibonacci Series, Subset Sum Problem

- **Randomized Algorithm**
  - Algorithm that make random choices for faster solutions known as Randomized Algorithm
  - Example - Randomized Quick Sort



## Complexity
***
- Algorithms that are classified on the basis of time taken to get a solution of any problem for input size
- Example O(N), O(N^2), O(N^3), Exponential time
- **Time-Complexity**
- **Space-Complexity**


### Recursion
***
- Recursion is the process in which a function is called by itself again & again.
- Example Print Factorial of a num using recursion
- ```code
     fact(n){
         if(n==0){
            return 1
         }
         else{
            return n*fact(n-1)
         }
     }
  
  ```
  
### Recursion vs Iteration
***
- | **Recursion** | **Iteration** |
  |---------------|---------------|
  | Recursion achieve repeation through repeated function calls | Iteration explicitly uses repeated structure |
  | Recursion terminates when base case is recognized | Iteration terminates when loop condition fails |
  | Recursion makes code smaller | Iteration makes code longer |
  | Recursion returns a value to the calling function | Iteration does not return any value |
  | Recursion is a slower than iteration | Iteration is faster |
  
 
## Game of Tower of Hannoi
***
- The Tower of Hanoi is a mathemaatical game or puzzle
- It consists of three vertical rods and a number of disks of different sizes which can be slide onto any rod
- The puzzle starts with the disk in a neat stack in ascending order of size on one rod, the smallest at the top, thus making a conical shape

- Possible number of moves for 5 disks, Tower of Hannoi
  - Possible num of moves = 2^n - 1
  -                       = 2^5 - 1 = 31


### **Binary Search Tree**
- It is a binary tree which may be either empty or satisfied following properties :- 
   - **Value of key in the left child is less than the value of root node**
   
   - **Value of Key in the right child is more than or equal to the value of the root**
   
   > **Binary Search + Binary Tree == B.S.T**
- B.S.T is used
   - To implement multi-level indexing in database
   - To implement various efficient algorithm
   - To manage Virtual Memory Access
   - To index various IP Address

> ***Worst Case Complexity for BST insertion O(H) where H = height of BST***


### **Concept of Huffman Coding**
***
- It is a particular type of optimal prefix code that is used for lossless data comparison
- It is an example of Greedy Algorithm
- It assigns variable length code to all the characters
- The code length of a character depends on How frequently it occurs in the given text
- The character which occurs most frequently gets the smallest code
- The character which occurs least frequently gets the largest code


### Searching
***
- Searching Algorithms are designed to check for an element or retrieve an element from any data structure where it is stored.
- There are two types of searching :- 
   - **Sequential Search**
   > **In this, the list or array is traversed sequentially and every element is checked.**
   - Linear Search


   - **Interval Search**
   > ***These type of searching algorithms are much more efficient than Linear Search as they repeatedly target the center of the search structure and divide the search space in half***
   - These algorithms are specifically designed for searching in sorted data-structures.
   - Binary Search


- **Linear Search**
  - Linear Search is linear time searching techniques in which a complete list/array is traversed in order to search an element
  - Time Complexity of Linear search = O(N) where n is num of elements in the list/array
