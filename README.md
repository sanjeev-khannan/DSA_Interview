# Common DSA Questions
I gathered some most common DSA interview questions from chatGPT and various sources. If you want to add something, Create a PR. Contributions welcome!

# Index
* Data Structures
    - [Array](#array)
    - [LinkedList](#linkedlist)
    - [Stack](#stack)
    - [Queue](#queue)
    - [Tree](#tree)
    - [Graph](#graph)
    - [Hash Table](#hash-table)
    - [Trie](#trie)
* Algorithms / Techniques
    - [Sliding Window](#sliding-window)
    - [Dynamic Programming](#dynamic-programming)
    - [Greedy](#greedy)
    - [Divide and Conquer](#divide-and-conquer)
    - [Backtracking](#backtracking)
    - [String-Related](#string-related)

## Array
Here are 15 of the most common array-related data structures and algorithms (DSA) questions:

1. **Two Sum**: Find two numbers in an array that add up to a specific target.

2. **Find the Missing Number**: Given an array containing n-1 distinct numbers in the range 1 to n, find the missing number.

3. **Maximum Subarray (Kadane's Algorithm)**: Find the contiguous subarray (containing at least one number) which has the largest sum.

4. **Merge Two Sorted Arrays**: Given two sorted arrays, merge them into a single sorted array.

5. **Find Duplicates in an Array**: Find all the duplicates in an array where each element is in the range 1 to n.

6. **Best Time to Buy and Sell Stock**: Find the maximum profit that can be made by buying and selling one stock.

7. **Product of Array Except Self**: Find the product of the array except for the element at the current index, without using division.

8. **Rotate Array**: Rotate an array to the right by k steps.

9. **Find the Majority Element**: Find the element that appears more than ⌊n/2⌋ times in an array.

10. **Find the Intersection of Two Arrays**: Find the intersection of two arrays (i.e., common elements).

11. **Maximum Product Subarray**: Find the contiguous subarray within an array that has the largest product.

12. **Trapping Rain Water**: Given n non-negative integers representing an elevation map, calculate how much water can be trapped.

13. **Subarray Sum Equals K**: Find the total number of continuous subarrays whose sum equals k.

14. **Longest Consecutive Sequence**: Given an unsorted array, find the length of the longest consecutive elements sequence.

15. **Minimum in Rotated Sorted Array**: Find the minimum element in a rotated sorted array.

## LinkedList
Here are 15 common data structure and algorithm (DSA) questions related to Linked Lists:

1. **Reverse a Linked List**: Given a linked list, reverse it in place.

2. **Detect a Cycle in a Linked List**: Determine if a linked list has a cycle and, if so, find the starting node of the cycle.

3. **Merge Two Sorted Linked Lists**: Merge two sorted linked lists into one sorted linked list.

4. **Find the Middle of a Linked List**: Use two pointers to find the middle node of a linked list.

5. **Remove N-th Node from End**: Remove the n-th node from the end of a linked list.

6. **Intersection of Two Linked Lists**: Determine the node at which two linked lists intersect.

7. **Copy List with Random Pointer**: Create a deep copy of a linked list where each node has an additional random pointer.

8. **Reorder List**: Given a linked list, reorder it in a specific way (e.g., L0 → Ln → L1 → Ln-1 → L2 → Ln-2).

9. **Palindrome Linked List**: Check if a linked list is a palindrome.

10. **Add Two Numbers**: Represent two numbers as linked lists and return their sum as a linked list.

11. **Remove Duplicates from Sorted Linked List**: Delete duplicates from a sorted linked list.

12. **Partition List**: Partition a linked list around a value x, such that all nodes less than x come before nodes greater than or equal to x.

13. **Rotate List**: Rotate a linked list to the right by k places.

14. **Split Circular Linked List**: Split a circular linked list into two linear linked lists.

15. **Kth Node from the End**: Find the k-th node from the end of a linked list without using extra space.

## Stack
Here are 15 common Stack data structure and algorithm (DSA) interview questions:

1. **Implement a Stack Using Arrays/LinkedList**: Create a stack data structure with basic operations (push, pop, top, isEmpty).

2. **Valid Parentheses**: Given a string containing just the characters `(`, `)`, `{`, `}`, `[` and `]`, determine if the input string is valid.

3. **Evaluate Reverse Polish Notation**: Evaluate an expression in Reverse Polish Notation (RPN).

4. **Daily Temperatures**: Given a list of daily temperatures, return a list of days until a warmer temperature.

5. **Largest Rectangle in Histogram**: Find the area of the largest rectangle that can be formed in a histogram represented by an array.

6. **Next Greater Element**: Given an array, find the next greater element for each element in the array.

7. **Sort a Stack**: Sort a stack such that the smallest elements are on the top.

8. **Check for Balanced Brackets**: Determine if the brackets in a given string are balanced.

9. **Implement Min Stack**: Design a stack that supports push, pop, top, and retrieving the minimum element in constant time.

10. **Binary Tree Preorder Traversal Using Stack**: Traverse a binary tree in preorder using a stack.

11. **Postfix to Infix Conversion**: Convert a postfix expression to an infix expression.

12. **Implement a Queue Using Stacks**: Create a queue using two stacks.

13. **Remove Duplicate Letters**: Given a string, remove duplicate letters so that every letter appears once and the result is in the smallest lexicographical order.

14. **Largest Parentheses Substring**: Find the length of the longest valid (well-formed) parentheses substring.

15. **Find the Maximum Depth of Nested Parentheses**: Calculate the maximum depth of nested parentheses in a given string.

## Queue
Here are 15 common Queue data structure and algorithm (DSA) interview questions:

1. **Implement a Queue Using Arrays/LinkedList**: Create a queue data structure with basic operations (enqueue, dequeue, front, isEmpty).

2. **Implement a Circular Queue**: Design a circular queue that efficiently utilizes space.

3. **Queue Using Stacks**: Implement a queue using two stacks.

4. **Reverse a Queue**: Write a function to reverse a given queue.

5. **Generate Binary Numbers**: Generate binary numbers from 1 to N using a queue.

6. **Level Order Traversal of a Binary Tree**: Traverse a binary tree in level order (BFS) using a queue.

7. **Sliding Window Maximum**: Find the maximum value in each sliding window of size K in an array.

8. **Implement a Priority Queue**: Create a priority queue data structure.

9. **First Non-Repeating Character in a Stream**: Find the first non-repeating character in a stream of characters.

10. **Josephus Problem**: Solve the Josephus problem using a queue.

11. **Sort a Queue**: Sort a queue using another queue or a stack.

12. **Connect All Level Order Siblings**: Connect nodes at the same level in a binary tree.

13. **Maximum of All Subarrays of Size K**: Find the maximum for each subarray of size K in an array.

14. **Rotting Oranges**: Given a grid of oranges, determine how long it will take for all oranges to rot.

15. **Design a Hit Counter**: Design a hit counter that counts the number of hits received in the past 5 minutes.

## Tree
Here are 20 common Tree data structure and algorithm (DSA) interview questions:

1. **Binary Tree Traversals**: Implement in-order, pre-order, and post-order traversals of a binary tree.

2. **Level Order Traversal**: Perform a level order traversal (BFS) of a binary tree.

3. **Height of a Binary Tree**: Find the height or depth of a binary tree.

4. **Check if a Tree is Balanced**: Determine if a binary tree is height-balanced.

5. **Validate a Binary Search Tree (BST)**: Check if a given tree is a valid binary search tree.

6. **Lowest Common Ancestor (LCA)**: Find the lowest common ancestor of two nodes in a binary tree.

7. **Diameter of a Binary Tree**: Calculate the diameter of a binary tree.

8. **Maximum Path Sum**: Find the maximum path sum in a binary tree.

9. **Serialize and Deserialize a Binary Tree**: Implement functions to serialize a binary tree to a string and deserialize it back.

10. **Invert a Binary Tree**: Write a function to invert a binary tree.

11. **K-th Smallest Element in a BST**: Find the k-th smallest element in a binary search tree.

12. **Flatten a Binary Tree to a Linked List**: Convert a binary tree into a flattened linked list in-place.

13. **Convert Sorted Array to BST**: Convert a sorted array into a height-balanced binary search tree.

14. **Path Sum**: Determine if there is a root-to-leaf path with a given sum.

15. **Sum of All Leaves**: Calculate the sum of all leaf nodes in a binary tree.

16. **Count Nodes in a Complete Binary Tree**: Count the number of nodes in a complete binary tree.

17. **Vertical Order Traversal**: Perform a vertical order traversal of a binary tree.

18. **Find a Path in a Maze**: Given a binary tree representing a maze, find a path from the root to a target leaf.

19. **Construct Binary Tree from Inorder and Postorder Traversal**: Rebuild a binary tree given its inorder and postorder traversal.

20. **Right Side View of a Binary Tree**: Return the values of the nodes you can see ordered from top to bottom when viewing the tree from the right side.

## Graph
Here are 20 common Graph data structure and algorithm (DSA) interview questions:

1. **Graph Representation**: Explain different ways to represent a graph (adjacency list, adjacency matrix).

2. **Depth-First Search (DFS)**: Implement DFS for a graph, both recursively and iteratively.

3. **Breadth-First Search (BFS)**: Implement BFS for a graph using a queue.

4. **Detect Cycle in a Graph**: Determine if a directed or undirected graph contains a cycle.

5. **Topological Sorting**: Perform a topological sort of a directed acyclic graph (DAG).

6. **Shortest Path in a Weighted Graph**: Use Dijkstra's algorithm to find the shortest path from a source vertex to all other vertices.

7. **Bellman-Ford Algorithm**: Implement the Bellman-Ford algorithm for finding the shortest path in a weighted graph.

8. **Floyd-Warshall Algorithm**: Use the Floyd-Warshall algorithm to find shortest paths between all pairs of vertices.

9. **Connected Components**: Find all connected components in an undirected graph.

10. **Minimum Spanning Tree (MST)**: Implement Prim's or Kruskal's algorithm to find the minimum spanning tree of a graph.

11. **Graph Cycle Detection in Directed Graph**: Use DFS to detect a cycle in a directed graph.

12. **Clone a Graph**: Create a deep copy of a graph represented with nodes and edges.

13. **Find the Number of Islands**: Given a grid representing water and land, find the number of islands using BFS/DFS.

14. **Shortest Path in an Unweighted Graph**: Use BFS to find the shortest path in an unweighted graph.

15. **Course Schedule**: Determine if it’s possible to finish all courses given prerequisites using topological sorting.

16. **Word Ladder**: Find the shortest transformation sequence from a start word to an end word using a dictionary.

17. **Bipartite Graph**: Check if a graph is bipartite using BFS or DFS.

18. **Longest Path in a Directed Acyclic Graph (DAG)**: Find the longest path in a DAG.

19. **Count Paths in a Grid**: Calculate the number of unique paths in a grid from the top-left to bottom-right corner.

20. **Traveling Salesman Problem (TSP)**: Solve the Traveling Salesman Problem using dynamic programming.

## Hash Table
Here are 15 common HashTable data structure and algorithm (DSA) interview questions:

1. **Two Sum**: Given an array of integers, return the indices of the two numbers that add up to a specific target.

2. **Group Anagrams**: Given an array of strings, group the anagrams together.

3. **Longest Substring Without Repeating Characters**: Find the length of the longest substring without repeating characters.

4. **Contains Duplicate**: Check if there are any duplicate elements in an array.

5. **Intersection of Two Arrays**: Find the intersection of two arrays and return the common elements.

6. **Valid Anagram**: Determine if two strings are anagrams of each other.

7. **Top K Frequent Elements**: Given a non-empty array of integers, return the k most frequent elements.

8. **Longest Consecutive Sequence**: Find the length of the longest consecutive elements sequence in an unsorted array.

9. **Find All Four Sum**: Given an array of integers, find all unique quadruplets that sum up to a target.

10. **Subarray Sum Equals K**: Find the total number of continuous subarrays whose sum equals a given value k.

11. **Minimum Window Substring**: Given two strings, find the minimum window substring that contains all characters of the second string.

12. **Ransom Note**: Determine if you can construct a ransom note from a given magazine string.

13. **Isomorphic Strings**: Check if two strings are isomorphic.

14. **Count Distinct Elements in Every Window of Size K**: Count the number of distinct elements in every window of size k in an array.

15. **Find All Duplicates in an Array**: Find all the elements that appear twice in an array.

## Trie
Here are 15 common Trie data structure and algorithm (DSA) interview questions:

1. **Implement a Trie**: Design and implement a trie (prefix tree) with insert, search, and delete operations.

2. **Search a Word in a Trie**: Given a trie, search for a specific word to determine if it exists in the trie.

3. **Autocomplete System**: Implement an autocomplete system that suggests words based on a given prefix.

4. **Longest Common Prefix**: Given an array of strings, find the longest common prefix using a trie.

5. **Word Search II**: Given a board of letters and a list of words, find all words in the board using a trie.

6. **Replace Words**: Given a dictionary of roots and a sentence, replace words in the sentence with their corresponding roots using a trie.

7. **Count Distinct Substrings**: Count the number of distinct substrings in a given string using a trie.

8. **Palindrome Pairs**: Given a list of words, find all unique pairs of words that can form palindromes when concatenated.

9. **Add and Search Word - Data Structure Design**: Implement a data structure that supports adding a word and searching for a word or a prefix.

10. **Spell Checker**: Design a spell checker that uses a trie to validate words against a dictionary and suggest corrections.

11. **Count Words in a Trie**: Count the number of words stored in a trie.

12. **Implement a Suffix Trie**: Design and implement a trie that supports storing and searching for suffixes of strings.

13. **Find Words in a Board**: Given a 2D board of letters and a list of words, find all words that can be formed in the board (similar to Word Search II).

14. **Add and Search for a Word with Wildcard**: Implement a function to search for a word in a trie that can include wildcard characters (e.g., ".").

15. **Longest Word in Dictionary**: Given a list of words, find the longest word that can be built by successive adding of characters (using a trie).

# Algorithms / Techniques
## Sliding Window
Here are 15 common Sliding Window data structure and algorithm (DSA) interview questions:

1. **Longest Substring Without Repeating Characters**: Find the length of the longest substring without repeating characters.

2. **Maximum Sum Subarray of Size K**: Given an array, find the maximum sum of a subarray of size K.

3. **Minimum Window Substring**: Given two strings, find the minimum window substring that contains all characters of the second string.

4. **Longest Repeating Character Replacement**: Find the length of the longest substring that can be obtained by replacing at most K characters.

5. **Count Anagrams in a String**: Count how many substrings in a given string are anagrams of another given string.

6. **Find All Anagrams in a String**: Given a string and a pattern, find all start indices of the anagrams of the pattern in the string.

7. **Subarray Product Less Than K**: Find the number of contiguous subarrays whose product is less than K.

8. **Sliding Window Maximum**: Find the maximum value in each sliding window of size K in an array.

9. **Minimum Size Subarray Sum**: Given an array of positive integers and a target sum, find the minimal length of a contiguous subarray whose sum is greater than or equal to the target sum.

10. **Permutation in String**: Check if one string is a permutation of another string using a sliding window approach.

11. **Longest Subarray with Sum K**: Find the length of the longest subarray with a sum equal to K.

12. **Character Replacement**: Find the longest substring containing the same letter you can get after performing at most K replacements.

13. **Number of Substrings with All 1's**: Count the number of substrings in a binary string that consist only of '1's.

14. **K-distant Unique Characters**: Count the number of substrings with exactly K unique characters.

15. **Longest Substring with At Most K Distinct Characters**: Find the length of the longest substring that contains at most K distinct characters.


## Dynamic Programming
Here are 20 common Dynamic Programming (DP) data structure and algorithm (DSA) interview questions:

1. **Fibonacci Sequence**: Calculate the nth Fibonacci number using dynamic programming.

2. **Climbing Stairs**: Determine the number of ways to climb to the top of a staircase with n steps, taking 1 or 2 steps at a time.

3. **Coin Change Problem**: Given an amount and coin denominations, find the minimum number of coins needed to make that amount.

4. **Longest Common Subsequence**: Find the length of the longest common subsequence between two strings.

5. **Longest Increasing Subsequence**: Determine the length of the longest increasing subsequence in an array.

6. **Edit Distance**: Calculate the minimum number of operations required to convert one string into another.

7. **0/1 Knapsack Problem**: Given weights and values of items, determine the maximum value that can be carried in a knapsack of a given capacity.

8. **Subset Sum Problem**: Check if there is a subset of a given set with a sum equal to a given target.

9. **House Robber**: Maximize the amount of money that can be robbed without robbing two adjacent houses.

10. **Maximum Subarray Sum (Kadane's Algorithm)**: Find the contiguous subarray with the maximum sum in an array.

11. **Unique Paths**: Calculate the number of unique paths from the top-left to the bottom-right of a grid.

12. **Maximum Product Subarray**: Find the contiguous subarray within an array that has the largest product.

13. **Word Break Problem**: Determine if a string can be segmented into space-separated words from a given dictionary.

14. **Partition Equal Subset Sum**: Determine if a given set can be partitioned into two subsets with equal sum.

15. **Minimum Path Sum**: Find the path with the minimum sum from the top-left to the bottom-right of a grid.

16. **Palindrome Partitioning**: Find the minimum number of cuts needed to partition a string into palindromic substrings.

17. **Maximum Length of Repeated Subarray**: Find the maximum length of a subarray that appears in two given arrays.

18. **Count All Palindromic Substrings**: Count how many palindromic substrings can be formed from a given string.

19. **Longest Palindromic Substring**: Find the longest palindromic substring in a given string.

20. **Gas Station Problem**: Determine if you can complete a circuit around a gas station given the gas and cost at each station.

## Greedy
Here are 15 common Greedy data structure and algorithm (DSA) interview questions:

1. **Activity Selection Problem**: Given a set of activities with start and finish times, select the maximum number of activities that don't overlap.

2. **Coin Change Problem**: Find the minimum number of coins needed to make a given amount using the largest denominations first.

3. **Fractional Knapsack Problem**: Maximize the total value in a knapsack by taking fractions of items, given their weights and values.

4. **Job Sequencing Problem**: Schedule jobs with deadlines to maximize profit, ensuring that only one job is scheduled at a time.

5. **Minimum Number of Platforms**: Given arrival and departure times of trains, find the minimum number of platforms required at a train station.

6. **Huffman Coding**: Build a Huffman tree to generate optimal binary codes for characters based on their frequencies.

7. **Merge Intervals**: Given a collection of intervals, merge overlapping intervals into the minimum number of intervals.

8. **Minimum Cost to Connect Ropes**: Find the minimum cost to connect a given set of ropes into one rope, where the cost to connect two ropes is the sum of their lengths.

9. **Maximum Meetings in One Room**: Determine the maximum number of meetings that can be conducted in a single room, given start and end times.

10. **Rearrange String K Distance Apart**: Reorganize a string so that no two adjacent characters are the same, using a greedy approach.

11. **Split Array into Consecutive Subsequences**: Determine if a given array can be split into consecutive subsequences.

12. **Find Minimum in Rotated Sorted Array**: Find the minimum element in a rotated sorted array using a greedy approach.

13. **Buy and Sell Stock with Cooldown**: Maximize profit from stock trading given a cooldown period between transactions.

14. **K-th Largest Element in an Array**: Find the K-th largest element in an unsorted array using a greedy selection technique.

15. **Maximize Sum of Non-Adjacent Elements**: Find the maximum sum of non-adjacent elements in an array.

## Divide and Conquer
Here are 15 common Divide and Conquer data structure and algorithm (DSA) interview questions:

1. **Merge Sort**: Implement the merge sort algorithm to sort an array.

2. **Quick Sort**: Implement the quick sort algorithm to sort an array.

3. **Find the Median of Two Sorted Arrays**: Given two sorted arrays, find the median of the combined sorted array.

4. **Closest Pair of Points**: Given a set of points, find the closest pair of points using the divide and conquer approach.

5. **Maximum Subarray Sum (Kadane’s Algorithm)**: Find the maximum sum of a contiguous subarray using divide and conquer.

6. **Count Inversions in an Array**: Count the number of inversions in an array, which can be done while sorting the array.

7. **Binary Search**: Implement binary search to find an element in a sorted array.

8. **Strassen's Algorithm for Matrix Multiplication**: Use divide and conquer to multiply two matrices more efficiently than the conventional method.

9. **Rotated Array Search**: Find the index of an element in a rotated sorted array using a modified binary search.

10. **Count the Number of Occurrences of an Element**: Find the count of occurrences of a given element in a sorted array using binary search.

11. **Largest Rectangle in Histogram**: Given an array representing the heights of bars in a histogram, find the area of the largest rectangle that can be formed.

12. **Kth Largest Element in an Array**: Find the Kth largest element in an unsorted array using the quickselect algorithm.

13. **Longest Common Prefix**: Given an array of strings, find the longest common prefix using a divide and conquer approach.

14. **Finding Peak Element**: Find a peak element in an array, where an element is considered a peak if it is greater than or equal to its neighbors.

15. **Power of a Number**: Calculate \(x^n\) (x raised to the power n) using the divide and conquer method (exponentiation by squaring).

## Backtracking
Here are 10 common Backtracking data structure and algorithm (DSA) interview questions:

1. **N-Queens Problem**: Place N queens on an N×N chessboard so that no two queens threaten each other.

2. **Sudoku Solver**: Implement a function to solve a Sudoku puzzle using backtracking.

3. **Permutations**: Generate all possible permutations of a given list of numbers or characters.

4. **Combination Sum**: Find all unique combinations of numbers that sum to a target value, allowing the same number to be used multiple times.

5. **Subsets**: Generate all possible subsets (the power set) of a given set of numbers.

6. **Word Search**: Given a 2D board of characters and a word, determine if the word can be constructed by a sequence of adjacent characters.

7. **Combination of Sum II**: Find all unique combinations of numbers that sum to a target, where each number can be used only once and duplicates are present.

8. **Knight's Tour Problem**: Determine if a knight can visit every square on a chessboard exactly once.

9. **Partition Equal Subset Sum**: Determine if a given set can be partitioned into two subsets with equal sum.

10. **Generate Parentheses**: Generate all combinations of well-formed parentheses for a given number of pairs.

## String-Related
Here are 20 of the most common string-related data structures and algorithms (DSA) questions that are frequently asked in coding interviews:

1. **Reverse a String**  
   - Reverse a given string.

2. **Check if a String is a Palindrome**  
   - Determine if a string reads the same forward and backward.

3. **Longest Palindromic Substring**  
   - Find the longest palindromic substring within a given string.

4. **Longest Common Prefix**  
   - Find the longest common prefix among an array of strings.

5. **Valid Anagram**  
   - Check if two strings are anagrams of each other.

6. **Implement strstr() or IndexOf()**  
   - Find the starting index of a substring within a given string.

7. **Group Anagrams**  
   - Group an array of strings into groups of anagrams.

8. **Longest Substring Without Repeating Characters**  
   - Find the length of the longest substring without repeating characters.

9. **Count and Say**  
   - Generate the nth term in the "count-and-say" sequence.

10. **String Compression**  
   - Compress a string by replacing repeated characters with the character followed by the count.

11. **Find All Permutations of a String**  
   - Generate all permutations of a given string.

12. **Check if String is Rotated**  
   - Check if one string is a rotation of another string.

13. **Minimum Window Substring**  
   - Find the smallest substring in s containing all characters of t.

14. **Remove All Adjacent Duplicates in String**  
   - Repeatedly remove all adjacent duplicates in a string.

15. **Roman to Integer**  
   - Convert a Roman numeral to an integer.

16. **Integer to Roman**  
   - Convert an integer to a Roman numeral.

17. **Longest Common Subsequence**  
   - Find the longest subsequence common to two strings.

18. **Zigzag Conversion**  
   - Arrange characters in a zigzag pattern and return a single string.

19. **Edit Distance (Levenshtein Distance)**  
   - Find the minimum number of operations required to convert one string to another.

20. **Basic Calculator**  
   - Implement a basic calculator to evaluate a simple expression string.
