# Coding Challenges

## Cracking the coding interview
### 1 Arrays and Strings
1. Is Unique: Implement an algorithm to determine if a string has all unique characters. What if you
cannot use additional data structures?
2. Check Permutation: Given two strings, write a method to decide if one is a permutation of the
other.
3. URLify: Write a method to replace all spaces in a string with '%20'. You may assume that the string
has sufficient space at the end to hold the additional characters, and that you are given the "true"
length of the string. (Note: If implementing in Java, please use a character array so that you can
perform this operation in place.)
**EXAMPLE**
Input: "Mr John Smith ", 13
Output: "Mr%20John%20Smith"
4. Palindrome Permutation: Given a string, write a function to check if it is a permutation of a palindrome. A palindrome is a word or phrase that is the same forwards and backwards. A permutation
is a rearrangement of letters. The palindrome does not need to be limited to just dictionary words.
**EXAMPLE**
Input: Tact Coa
Output: True (permutations: "taco cat", "atco eta", etc.)
5. One Away: There are three types of edits that can be performed on strings: insert a character,
remove a character, or replace a character. Given two strings, write a function to check if they are
one edit (or zero edits) away.
**EXAMPLE**
pale, ple -> true
pales, pale -> true
pale, bale -> true
pale, bake -> false
6. String Compression: Implement a method to perform basic string compression using the counts
of repeated characters. For example, the string aabcccccaaa would become a2blc5a3. If the
"compressed" string would not become smaller than the original string, your method should return
the original string. You can assume the string has only uppercase and lowercase letters (a - z).
7. Rotate Matrix: Given an image represented by an NxN matrix, where each pixel in the image is 4
bytes, write a method to rotate the image by 90 degrees. Can you do this in place?
8. Zero Matrix: Write an algorithm such that if an element in an MxN matrix is 0, its entire row and
column are set to 0.
9. String Rotation:Assumeyou have a method isSubstringwhich checks if oneword is a substring
of another. Given two strings, sl and s2, write code to check if s2 is a rotation of sl using only one
call to isSubstring (e.g., "waterbottle" is a rotation of"erbottlewat").

### 2 Linked Lists
1. Remove Dups! Write code to remove duplicates from an unsorted linked list.
FOLLOW UP
How would you solve this problem if a temporary buffer is not allowed?
2. Return Kth to Last: Implement an algorithm to find the kth to last element of a singly linked list.
3. Delete Middle Node: Implement an algorithm to delete a node in the middle (i.e., any node but
the first and last node, not necessarily the exact middle) of a singly linked list, given only access to
that node.
**EXAMPLE**
Input:the node c from the linked lista->b->c->d->e->f
Result: nothing is returned, but the new linked list looks like a->b->d->e->f
4. Partition: Write code to partition a linked list around a value x, such that all nodes less than x come
before all nodes greater than or equal to x. If x is contained within the list, the values of x only need
to be after the elements less than x (see below). The partition element x can appear anywhere in the
"right partition"; it does not need to appear between the left and right partitions.
**EXAMPLE**
Input: 3 -> 5 -> 8 -> 5 -> 10 -> 2 -> 1 [partition= 5]
Output: 3 -> 1 -> 2 -> 10 -> 5 -> 5 -> 8


5. Sum Lists: You have two numbers represented by a linked list, where each node contains a single
digit. The digits are stored in reverse order, such that the 1 's digit is at the head of the list. Write a
function that adds the two numbers and returns the sum as a linked list.
**EXAMPLE**
Input: (7-> 1 -> 6) + (5 -> 9 -> 2).That is,617 + 295.
Output: 2 -> 1 -> 9. That is, 912.
FOLLOW UP
Suppose the digits are stored in forward order. Repeat the above problem.
**EXAMPLE**
Input:(6 -> 1 -> 7) + (2 -> 9 -> 5).That is,617 + 295.
Output: 9 -> 1 -> 2. That is, 912.
6. Palindrome: Implement a function to check if a linked list is a palindrome.
7. Intersection: Given two (singly) linked lists, determine if the two lists intersect. Return the intersecting node. Note that the intersection is defined based on reference, not value. That is, if the kth
node of the first linked list is the exact same node (by reference) as the jth node of the second
linked list, then they are intersecting.
8. Loop Detection: Given a circular linked list, implement an algorithm that returns the node at the
beginning of the loop.
DEFINITION
Circular linked list: A (corrupt) linked list in which a node's next pointer points to an earlier node, so
as to make a loop in the linked list.
**EXAMPLE**
Input: A -> B -> C -> D -> E -> C [the same C as earlier]
Output: C

### 3 Stacks and Queues
1. Three in One: Describe how you could use a single array to implement three stacks.
2. Stack Min: How would you design a stack which, in addition to push and pop, has a function min
which returns the minimum element? Push, pop and min should all operate in 0(1) time.
3. Stack of Plates: Imagine a (literal) stack of plates. If the stack gets too high, it might topple.
Therefore, in real life, we would likely start a new stack when the previous stack exceeds some
threshold. Implement a data structure SetOfStacks that mimics this. SetO-fStacks should be
composed of several stacks and should create a new stack once the previous one exceeds capacity.
SetOfStacks. push() and SetOfStacks. pop() should behave identically to a single stack
(that is, pop () should return the same values as it would if there were just a single stack).
FOLLOW UP
Implement a function popAt ( int index) which performs a pop operation on a specific sub-stack.
4. Queue via Stacks: Implement a MyQueue class which implements a queue using two stacks.
5. Sort Stack: Write a program to sort a stack such that the smallest items are on the top. You can use
an additional temporary stack, but you may not copy the elements into any other data structure
(such as an array). The stack supports the following operations: push, pop, peek, and is Empty.
6. Animal Shelter: An animal shelter, which holds only dogs and cats, operates on a strictly"first in, first
out" basis. People must adopt either the "oldest" (based on arrival time) of all animals at the shelter,
or they can select whether they would prefer a dog or a cat (and will receive the oldest animal of
that type). They cannot select which specific animal they would like. Create the data structures to
maintain this system and implement operations such as enqueue, dequeueAny, dequeueDog,
and dequeueCat. You may use the built-in Linked list data structure.

### 4 Trees and Graphs
1. Route Between Nodes: Given a directed graph, design an algorithm to find out whether there is a
route between two nodes.
2. Minimal Tree: Given a sorted (increasing order) array with unique integer elements, write an algorithm to create a binary search tree with minimal height.
3. List of Depths: Given a binary tree, design an algorithm which creates a linked list of all the nodes
at each depth (e.g., if you have a tree with depth D, you'll have D linked lists).
4. Check Balanced: Implement a function to check if a binary tree is balanced. For the purposes of
this question, a balanced tree is defined to be a tree such that the heights of the two subtrees of any
node never differ by more than one.
5. Validate BST: Implement a function to check if a binary tree is a binary search tree.
6. Successor: Write an algorithm to find the "next" node (i.e., in-order successor) of a given node in a
binary search tree. You may assume that each node has a link to its parent.
7. Build Order: You are given a list of projects and a list of dependencies (which is a list of pairs of
projects, where the second project is dependent on the first project). All of a project's dependencies
must be built before the project is. Find a build order that will allow the projects to be built. If there
is no valid build order, return an error.
**EXAMPLE**
Input:
projects: a, b, c, d, e, f
dependencies: (a, d), (f, b), (b, d), (f, a), (d, c)
Output: f, e, a, b, d, c
8. First Common Ancestor: Design an algorithm and write code to find the first common ancestor
of two nodes in a binary tree. Avoid storing additional nodes in a data structure. NOTE: This is not
necessarily a binary search tree.
9. BST Sequences: A binary search tree was created by traversing through an array from left to right
and inserting each element. Given a binary search tree with distinct elements, print all possible
arrays that could have led to this tree.
**EXAMPLE**
Input: | 1 | <--- 2 ---> | 3 |
Output: {2, 1, 3}, {2, 3, 1}
10. Check Subtree: Tl and T2 are two very large binary trees, with Tl much bigger than T2. Create an
algorithm to determine if T2 is a subtree of Tl.
A tree T2 is a subtree of Tl if there exists a node n in Tl such that the subtree of n is identical to T2.
That is, if you cut off the tree at node n, the two trees would be identical.
11. Random Node: You are implementing a binary tree class from scratch which, in addition to
insert, find, and delete, has a method getRandomNode() which returns a random node
from the tree. All nodes should be equally likely to be chosen. Design and implement an algorithm
for getRandomNode, and explain how you would implement the rest of the methods.
12. Paths with Sum: You are given a binary tree in which each node contains an integer value (which
might be positive or negative). Design an algorithm to count the number of paths that sum to a
given value. The path does not need to start or end at the root or a leaf, but it must go downwards
(traveling only from parent nodes to child nodes).

### 5 Bit Manipulation
1. Insertion: You are given two 32-bit numbers, N and M, and two bit positions, i and
j. Write a method to insert M into N such that M starts at bit j and ends at bit i. You
can assume that the bits j through i have enough space to fit all of M. That is, if
M = 10011, you can assume that there are at least 5 bits between j and i. You would not, for
example, have j = 3 and i = 2, because M could not fully fit between bit 3 and bit 2.
**EXAMPLE**
Input: N 10000000000, M
Output: N = 10001001100
2. Binary to String: Given a real number between O and 1 (e.g., 0.72) that is passed in as a double, print
the binary representation. If the number cannot be represented accurately in binary with at most 32
characters, print "ERROR:'
3. Flip Bit to Win: You have an integer and you can flip exactly one bit from a 0 to a 1. Write code to
find the length of the longest sequence of ls you could create.
**EXAMPLE**
Input: 1775
Output: 8
(or: 11011101111)
4. Next Number: Given a positive integer, print the next smallest and the next largest number that
have the same number of 1 bits in their binary representation.
5. Debugger: Explain what the following code does: ( ( n & ( n-1)) == 0).
6. Conversion: Write a function to determine the number of bits you would need to flip to convert
integer A to integer B.
**EXAMPLE**
Input: 29 (or: 11101), 15 (or: 01111)
Output: 2
7. Pairwise Swap: Write a program to swap odd and even bits in an integer with as few instructions as
possible (e.g., bit 0 and bit 1 are swapped, bit 2 and bit 3 are swapped, and so on).
8. Draw Line: A monochrome screen is stored as a single array of bytes, allowing eight consecutive
pixels to be stored in one byte. The screen has width w, where w is divisible by 8 (that is, no byte will
be split across rows). The height of the screen, of course, can be derived from the length of the array
and the width. Implement a function that draws a horizontal line from ( xl, y) to ( x2, y).
The method signature should look something like:
drawline(byte[] screen, int width, int xl, int x2, int y)

### 6 Math and Logic Puzzles
1. The Heavy Pill: You have 20 bottles of pills. 19 bottles have 1.0 gram pills, but one has pills of weight
1.1 grams. Given a scale that provides an exact measurement, how would you find the heavy bottle?
You can only use the scale once.
2. Basketball: You have a basketball hoop and someone says that you can play one of two games.
Game 1: You get one shot to make the hoop.
Game 2: You get three shots and you have to make two of three shots.
If p is the probability of making a particular shot, for which values of p should you pick one game
or the other?
3. Dominos: There is an 8x8 chessboard in which two diagonally opposite corners have been cut off.
You are given 31 dominos, and a single domino can cover exactly two squares. Can you use the 31
dominos to cover the entire board? Prove your answer (by providing an example or showing why
it's impossible).
4. Ants on a Triangle: There are three ants on different vertices of a triangle. What is the probability of
collision (between any two or all of them) if they start walking on the sides of the triangle? Assume
that each ant randomly picks a direction, with either direction being equally likely to be chosen, and
that they walk at the same speed.
Similarly, find the probability of collision with n ants on an n-vertex polygon.
5. Jugs of Water: You have a five-quart jug, a three-quart jug, and an unlimited supply of water (but
no measuring cups). How would you come up with exactly four quarts of water? Note that the jugs
are oddly shaped, such that filling up exactly "half" of the jug would be impossible.
6. Blue-Eyed Island: A bunch of people are living on an island, when a visitor comes with a strange
order: all blue-eyed people must leave the island as soon as possible. There will be a flight out at
8:00 pm every evening. Each person can see everyone else's eye color, but they do not know their
own (nor is anyone allowed to tell them). Additionally, they do not know how many people have
blue eyes, although they do know that at least one person does. How many days will it take the
blue-eyed people to leave?
7. The Apocalypse: In the new post-apocalyptic world, the world queen is desperately concerned
about the birth rate. Therefore, she decrees that all families should ensure that they have one girl or
else they face massive fines. If all families abide by this policy that is, they have continue to have
children until they have one girl, at which point they immediately stop-what will the gender ratio
of the new generation be? (Assume that the odds of someone having a boy or a girl on any given
pregnancy is equal.) Solve this out logically and then write a computer simulation of it.
8. The Egg Drop Problem: There is a building of 100 floors. If an egg drops from the Nth floor or
above, it will break. If it's dropped from any floor below, it will not break. You're given two eggs. Find
N, while minimizing the number of drops for the worst case.
9. 100 Lockers: There are 100 closed lockers in a hallway. A man begins by opening all 100 lockers.
Next, he closes every second locker. Then, on his third pass, he toggles every third locker (closes it if
it is open or opens it if it is closed). This process continues for 100 passes, such that on each pass i,
the man toggles every ith locker. After his 100th pass in the hallway, in which he toggles only locker #100, how many lockers are open?
10. Poison: You have 1000 bottles of soda, and exactly one is poisoned. You have 10 test strips which
can be used to detect poison. A single drop of poison will turn the test strip positive permanently.
You can put any number of drops on a test strip at once and you can reuse a test strip as many times
as you'd like (as long as the results are negative). However, you can only run tests once per day and
it takes seven days to return a result. How would you figure out the poisoned bottle in as few days
as possible?
FOLLOW UP
Write code to simulate your approach.

### 7 Object-Oriented Design
1. Deck of Cards: Design the data structures for a generic deck of cards. Explain how you would
subclass the data structures to implement blackjack.
2. Call Center: Imagine you have a call center with three levels of employees: respondent, manager,
and director. An incoming telephone call must be first allocated to a respondent who is free. If the
respondent can't handle the call, he or she must escalate the call to a manager. If the manager is not
free or not able to handle it, then the call should be escalated to a director. Design the classes and
data structures for this problem. Implement a method dispatchCall() which assigns a call to
the first available employee.
3. Jukebox: Design a musical jukebox using object oriented principles.
4. Parking Lot: Design a parking lot using object-oriented principles.
5. Online Book Reader: Design the data structures for an online book reader system.
6. Jigsaw: Implement an NxN jigsaw puzzle. Design the data structures and explain an algorithm to
solve the puzzle. You can assume that you have a fitsWith method which, when passed two
puzzle edges, returns true if the two edges belong together.
7. Chat Server: Explain how you would design a chat server. In particular, provide details about the
various backend components, classes, and methods. What would be the hardest problems to solve?
8. Othello: Othello is played as follows: Each Othello piece is white on one side and black on the other.
When a piece is surrounded by its opponents on both the left and right sides, or both the top and
bottom, it is said to be captured and its color is flipped. On your turn, you must capture at least one
of your opponent's pieces. The game ends when either user has no more valid moves. The win is
assigned to the person with the most pieces. Implement the object-oriented design for Othello.
9. Circular Array: Implement a CircularArray class that supports an array-like data structure which
can be efficiently rotated. If possible, the class should use a generic type (also called a template), and
should support iteration via the standard f or (Obj o : circularArray) notation.
10. Minesweeper: Design and implement a text-based Minesweeper game. Minesweeper is the classic
single-player computer game where an NxN grid has B mines (or bombs) hidden across the grid. The
remaining cells are either blank or have a number behind them. The numbers reflect the number of
bombs in the surrounding eight cells. The user then uncovers a cell. If it is a bomb, the player loses.
If it is a number, the number is exposed. If it is a blank cell, this cell and all adjacent blank cells (up to and including the surrounding numeric cells) are exposed. The player wins when all non-bomb cells
are exposed. The player can also flag certain places as potential bombs. This doesn't affect game
play, other than to block the user from accidentally clicking a cell that is thought to have a bomb.
(Tip for the reader: if you're not familiar with this game, please play a few rounds on line first.)
11. File System: Explain the data structures and algorithms that you would use to design an in-memory
file system. Illustrate with an example in code where possible.
12. Hash Table: Design and implement a hash table which uses chaining (linked lists) to handle collisions.

### 8 Recursion and Dynamic Programming
1. Triple Step: A child is running up a staircase with n steps and can hop either 1 step, 2 steps, or 3
steps at a time. Implement a method to count how many possible ways the child can run up the
stairs.
2. Robot in a Grid: Imagine a robot sitting on the upper left corner of grid with r rows and c columns.
The robot can only move in two directions, right and down, but certain cells are "off limits" such that
the robot cannot step on them. Design an algorithm to find a path for the robot from the top left to
the bottom right.
3. Magic Index: A magic index in an array A [ 0 ••• n -1] is defined to be an index such that A[ i] =
i. Given a sorted array of distinct integers, write a method to find a magic index, if one exists, in
array A.
FOLLOW UP
What if the values are not distinct?
4. Power Set: Write a method to return all subsets of a set.
5. Recursive Multiply: Write a recursive function to multiply two positive integers without using the asterisk ( * ) operator.You can use addition, subtraction, and bit shifting, but you should minimize the number of those operations.
6. Towers of Hanoi: In the classic problem of the Towers of Hanoi, you have 3 towers and N disks of
different sizes which can slide onto any tower. The puzzle starts with disks sorted in ascending order
of size from top to bottom (i.e., each disk sits on top of an even larger one). You have the following
constraints:
(1) Only one disk can be moved at a time.
(2) A disk is slid off the top of one tower onto another tower.
(3) A disk cannot be placed on top of a smaller disk.
Write a program to move the disks from the first tower to the last using stacks.
7. Permutations without Dups: Write a method to compute all permutations of a string of unique
characters.
8. Permutations with Dups: Write a method to compute all permutations of a string whose characters are not necessarily unique. The list of permutations should not have duplicates.
9. Parens: Implement an algorithm to print all valid (e.g., properly opened and closed) combinations
of n pairs of parentheses.
**EXAMPLE**
Input: 3
Output: ( ( () ) ) , ( () () ) , ( () ) () , () ( () ) , () () ()
10. Paint Fill: Implement the "paint fill" function that one might see on many image editing programs.
That is, given a screen (represented by a two-dimensional array of colors), a point, and a new color,
fill in the surrounding area until the color changes from the original color.
11. Coins: Given an infinite number of quarters (25 cents), dimes (10 cents), nickels (5 cents), and
pennies (1 cent), write code to calculate the number of ways of representing n cents.
12. Eight Queens: Write an algorithm to print all ways of arranging eight queens on an 8x8 chess board
so that none of them share the same row, column, or diagonal. In this case, "diagonal" means all
diagonals, not just the two that bisect the board.
13. Stack of Boxes: You have a stack of n boxes, with widths wi
, heights hi
, and depths di
. The boxes
cannot be rotated and can only be stacked on top of one another if each box in the stack is strictly
larger than the box above it in width, height, and depth. Implement a method to compute the
height of the tallest possible stack. The height of a stack is the sum of the heights of each box.
14. Boolean Evaluation: Given a boolean expression consisting of the symbols 0 (false), 1 (true), &
(AND), I (OR), and /\ (XOR), and a desired boolean result value result, implement a function to
count the number of ways of parenthesizing the expression such that it evaluates to result.
**EXAMPLE**
countEval("l /\01011", false) -> 2
countEval("0&0&0&1/\ll0", true) -> 10

### 9 System Design and Scalability
1. Stock Data: Imagine you are building some sort of service that will be called by up to 1,000 client
applications to get simple end-of day stock price information (open, close, high, low). You may
assume that you already have the data, and you can store it in any format you wish. How would you
design the client-facing service that provides the information to client applications?You are responsible for the development, rollout, and ongoing monitoring and maintenance of the feed. Describe
the different methods you considered and why you would recommend your approach. Your service
can use any technologies you wish, and can distribute the information to the client applications in
any mechanism you choose.
2. Social Network: How would you design the data structures for a very large social network like Facebook or Linked In? Describe how you would design an algorithm to show the shortest path between
two people (e.g., Me -> Bob -> Susan -> Jason -> You).
3. Web Crawler: If you were designing a web crawler, how would you avoid getting into infinite loops?
4. Duplicate URLs: You have 10 billion URLs. How do you detect the duplicate documents? In this
case, assume "duplicate" means that the URLs are identical.
5. Cache: Imagine a web server for a simplified search engine. This system has 100 machines to
respond to search queries, which may then call out using processSearch ( string query) to
another cluster of machines to actually get the result. The machine which responds to a given query
is chosen at random, so you cannot guarantee that the same machine will always respond to the
same request. The method processSearch is very expensive. Design a caching mechanism for
the most recent queries. Be sure to explain how you would update the cache when data changes.
6. Sales Rank: A large eCommerce company wishes to list the best-selling products, overall and by
category. For example, one product might be the #1056th best-selling product overall but the #13th
best-selling product under "Sports Equipment" and the #24th best-selling product under "Safety."
Describe how you would design this system.
7. Personal Financial Manager: Explain how you would design a personal financial manager (like
Mint.com). This system would connect to your bank accounts, analyze your spending habits, and
make recommendations.
8. Pastebin: Design a system like Pastebin, where a user can enter a piece of text and get a randomly
generated URL to access it.

### 10 Sorting and Searching
1. Sorted Merge: You are given two sorted arrays, A and B, where A has a large enough buffer at the
end to hold B. Write a method to merge B into A in sorted order.
2. Group Anagrams: Write a method to sort an array of strings so that all the anagrams are next to
each other.
3. Search in Rotated Array: Given a sorted array of n integers that has been rotated an unknown
number of times, write code to find an element in the array. You may assume that the array was
originally sorted in increasing order.
**EXAMPLE**
Input:findSin{lS, 16, 19, 20, 25, 1, 3, 4, 5, 7, 10, 14}
Output: 8 (the index of 5 in the array)
4. Sorted Search, No Size: You are given an array like data structure Listy which lacks a size
method. It does, however, have an elementAt ( i) method that returns the element at index i in
0( 1) time. If i is beyond the bounds of the data structure, it returns -1. (For this reason, the data
structure only supports positive integers.) Given a Li sty which contains sorted, positive integers,
find the index at which an element x occurs. If x occurs multiple times, you may return any index.
5. Sparse Search: Given a sorted array of strings that is interspersed with empty strings, write a
method to find the location of a given string.
**EXAMPLE**
Input: ball,{"at","",'"',"", "ball","","", "car", "",'"', "dad",'"',""}
Output:4
6. Sort Big File: Imagine you have a 20 GB file with one string per line. Explain how you would sort
the file.
7. Missing Int: Given an input file with four billion non-negative integers, provide an algorithm to
generate an integer that is not contained in the file. Assume you have 1 GB of memory available for
this task.
FOLLOW UP
What if you have only 10 MB of memory? Assume that all the values are distinct and we now have
no more than one billion non-negative integers.
8. Find Duplicates: You have an array with all the numbers from 1 to N, where N is at most 32,000. The
array may have duplicate entries and you do not know what N is. With only 4 kilobytes of memory
available, how would you print all duplicate elements in the array?
9. Sorted Matrix Search: Given an M x N matrix in which each row and each column is sorted in
ascending order, write a method to find an element.
10. Rank from Stream: Imagine you are reading in a stream of integers. Periodically, you wish to be able
to look up the rank of a numberx (the number of values less than or equal to x). lmplementthe data
structures and algorithms to support these operations. That is, implement the method track ( int x), which is called when each number is generated, and the method getRankOfNumber(int x), which returns the number of values less than or equal to x (not including x itself).
**EXAMPLE**
Stream (in order of appearance): 5, 1, 4, 4, 5, 9, 7, 13, 3
getRankOfNumber(l) = 0
getRankOfNumber(3) = 1
getRankOfNumber(4) = 3
11. Peaks and Valleys: In an array of integers, a "peak" is an element which is greater than or equal to
the adjacent integers and a "valley" is an element which is less than or equal to the adjacent integers. For example, in the array {5, 8, 6, 2, 3, 4, 6}, {8, 6} are peaks and {5, 2} are valleys. Given an array
of integers, sort the array into an alternating sequence of peaks and valleys.
**EXAMPLE**
Input: {5, 3, 1, 2, 3}
Output: {5, 1, 3, 2, 3}

### 11 Testing
1. Mistake: Find the mistake(s) in the following code:
unsigned inti;
for (i = 100; i >= 0; --i)
printf("%d\n", i);
2. Random Crashes: You are given the source to an application which crashes when it is run. After
running it ten times in a debugger, you find it never crashes in the same place. The application is
single threaded, and uses only the C standard library. What programming errors could be causing
this crash? How would you test each one?
3. ChessTest:We have the following method used in a chess game: boolean canMoveTo(int x,
int y). This method is part of the Piece class and returns whether or not the piece can move to
position (x, y). Explain how you would test this method.
4. No Test Tools: How would you load test a webpage without using any test tools?
5. Test a Pen: How would you test a pen?
6. Test an ATM: How would you test an ATM in a distributed banking system?

### 12 C and C++
1. Last K Lines: Write a method to printthe last Klines of an input file using C++.
2. Reverse String: Implement a function void reverse( char* str) in C or C++ which reverses
a null-terminated string.
3. Hash Table vs. STL Map: Compare and contrast a hash table and an STL map. How is a hash table
implemented? If the number of inputs is small, which data structure options can be used instead of
a hash table?
4. Virtual Functions: How do virtual functions work in C++?
5. Shallow vs. Deep Copy: What is the difference between deep copy and shallow copy? Explain how
you would use each.
6. Volatile: What is the significance of the keyword "volatile" in C?
7. Virtual Base Class: Why does a destructor in base class need to be declared virtual?
8. Copy Node: Write a method that takes a pointer to a Node structure as a parameter and returns a
complete copy of the passed in data structure. The Node data structure contains two pointers to
other Nodes.
9. Smart Pointer: Write a smart pointer class. A smart pointer is a data type, usually implemented with
templates, that simulates a pointer while also providing automatic garbage collection. It automatically counts the number of references to a SmartPointer<T*> object and frees the object of type
T when the reference count hits zero.
10. Malloc: Write an aligned malloc and free function that supports allocating memory such that the
memory address returned is divisible by a specific power of two.
**EXAMPLE**
align_malloc (1000, 128) will return a memory address that is a multiple of 128 and that points
to memory of size 1000 bytes.
aligned_ free () will free memory allocated by align_malloc.
11. 2D Alloc: Write a function in C called my2DA1loc which allocates a two-dimensional array. Minimize the number of calls to malloc and make sure that the memory is accessible by the notation
arr[i][j].

### 13 Java
1. Private Constructor: In terms of inheritance, what is the effect of keeping a constructor private?
2. Return from Finally: In Java, does the finally block get executed if we insert a return statement inside the try block of a try-catch-finally?
3. Final, etc.: What is the difference between final, finally, and finalize?
4. Generics vs. Templates: Explain the difference between templates in C ++ and generics in Java.
5. TreeMap, HashMap, LinkedHashMap: Explain the differences between TreeMap, HashMap, and
LinkedHashMap. Provide an example of when each one would be best.
6. Object Reflection: Explain what object reflection is in Java and why it is useful.
7. Lambda Expressions: There is a class Country that has methods getContinent() and
getPopulation(). Write a function int getPopulation(List<Country> countries,
String continent) that computes the total population of a given continent, given a list of all
countries and the name of a continent.
8. Lambda Random: Using Lambda expressions, write a function List<Integer>
getRandomSubset ( List< Integer> list) that returns a random subset of arbitrary size. All
subsets (including the empty set) should be equally likely to be chosen.

### 14 Databases
1. Multiple Apartments: Write a SOL query to get a list of tenants who are renting more than one
apartment.
2. Open Requests: Write a SQL query to get a list of all buildings and the number of open requests
(Requests in which status equals 'Open').
3. Close All Requests: Building #11 is undergoing a major renovation. Implement a query to close all
requests from apartments in this building.
4. Joins: What are the different types of joins? Please explain how they differ and why certain types
are better in certain situations.
5. Denormalization: What is denormalization? Explain the pros and cons.
6. Entity-Relationship Diagram: Draw an entity-relationship diagram for a database with companies,
people, and professionals (people who work for companies).
7. Design Grade Database: Imagine a simple database storing information for students' grades.
Design what this database might look like and provide a SQL query to return a list of the honor roll
students (top 10%), sorted by their grade point average.

### 15 Threads and Locks
1. Thread vs. Process: What's the difference between a thread and a process?
2. Context Switch: How would you measure the time spent in a context switch?
3. Dining Philosophers: In the famous dining philosophers problem, a bunch of philosophers are
sitting around a circular table with one chopstick between each of them. A philosopher needs
both chopsticks to eat, and always picks up the left chopstick before the right one. A deadlock
could potentially occur if all the philosophers reached for the left chopstick at the same time. Using
threads and locks, implement a simulation of the dining philosophers problem that prevents deadlocks.
4. Deadlock-Free Class: Design a class which provides a lock only if there are no possible deadlocks.
5. Call In Order: Suppose we have the following code:

    ```java
    public class Foo {
    public Foo() { ... }
    public void first() { ... }
    public void second() { ... }
    public void third() { ... }
    }
    ```
    The same instance of Foo will be passed to three different threads. ThreadA will call first,
    threads will call second, and thread( will call third. Design a mechanism to ensure that
    first is called before second and second is called before third.
{:start="6"}
6. Synchronized Methods: You are given a class with synchronized method A and a normal method
B. If you have two threads in one instance of a program, can they both execute A at the same time?
Can they execute A and B at the same time?
7. FizzBuzz: In the classic problem FizzBuzz, you are told to print the numbers from 1 to n. However, when the number is divisible by 3, print "Fizz". When it is divisible by 5, print "Buzz". When it is divisible by 3 and 5, print "FizzBuzz". In this problem, you are asked to do this in a multithreaded way. Implement a multithreaded version of FizzBuzz with four threads. One thread checks for divisibility of 3 and prints "Fizz". Another thread is responsible for divisibility of 5 and prints"Buzz''. A third thread is responsible for divisibility of 3 and 5 and prints "FizzBuzz". A fourth thread does the numbers.

### 16 Moderate
1. Number Swapper: Write a function to swap a number in place (that is, without temporary variables).
2. Word Frequencies: Design a method to find the frequency of occurrences of any given word in a
book. What if we were running this algorithm multiple times?
3. Intersection: Given two straight line segments (represented as a start point and an end point),
compute the point of intersection, if any.
4. Tic Tac Win: Design an algorithm to figure out if someone has won a game of tic-tac-toe.
5. Factorial Zeros: Write an algorithm which computes the number of trailing zeros in n factorial.
6. Smallest Difference: Given two arrays of integers, compute the pair of values (one value in each
array) with the smallest (non-negative) difference. Return the difference.
**EXAMPLE**
Input: {1, 3, 15, 11, 2}, {23, 127,235, 19, 8}
Output: 3. That is, the pair (11, 8).
7. Number Max: Write a method that finds the maximum of two numbers. You should not use if-else
or any other comparison operator.
8. English Int: Given any integer, print an English phrase that describes the integer (e.g., "One Thousand, Two Hundred Thirty Four").
9. Operations: Write methods to implement the multiply, subtract, and divide operations for integers.
The results of all of these are integers. Use only the add operator.
10. Living People: Given a list of people with their birth and death years, implement a method to
compute the year with the most number of people alive. You may assume that all people were born
between 1900 and 2000 (inclusive). If a person was alive during any portion of that year, they should
be included in that year's count. For example, Person (birth= 1908, death= 1909) is included in the
counts for both 1908 and 1909.
11. Diving Board: You are building a diving board by placing a bunch of planks of wood end-to-end.
There are two types of planks, one of length shorter and one of length longer. You must use
exactly K planks of wood. Write a method to generate all possible lengths for the diving board.
12. XML Encoding: Since XML is very verbose, you are given a way of encoding it where each tag gets
mapped to a pre-defined integer value. The language/grammar is as follows:
Element --> Tag Attributes END Children END
Attribute --> Tag Value
END --> 0
Tag --> some predefined mapping to int
Value --> string value
For example, the following XML might be converted into the compressed string below (assuming a
mapping of family -> 1, person ->2, firstName -> 3, lastName -> 4, state
-> 5).

    ```xml
    <family lastName="McDowell" state="CA">
    <person firstName="Gayle">Some Message</person>
    </family>
    ```
    Becomes:
    1 4 McDowell 5 CA 0 2 3 Gayle 0 Some Message 0 0
    Write code to print the encoded version of an XML element (passed in Element and Attribute objects).
{:start="13"}
13. Bisect Squares: Given two squares on a two-dimensional plane, find a line that would cut these two
squares in half. Assume that the top and the bottom sides of the square run parallel to the x-axis.
14. Best Line: Given a two-dimensional graph with points on it, find a line which passes the most
number of points.
15. Master Mind: The Game of Master Mind is played as follows:
The computer has four slots, and each slot will contain a ball that is red (R). yellow (Y). green (G) or
blue (B). For example, the computer might have RGGB (Slot #1 is red, Slots #2 and #3 are green, Slot #4 is blue).
You, the user, are trying to guess the solution. You might, for example, guess YRGB.
When you guess the correct color for the correct slot, you get a "hit:' If you guess a color that exists
but is in the wrong slot, you get a "pseudo-hit:' Note that a slot that is a hit can never count as a
pseudo-hit.
For example, if the actual solution is RGBY and you guess GGRR, you have one hit and one pseudo-hit.
Write a method that, given a guess and a solution, returns the number of hits and pseudo-hits.
16. Sub Sort: Given an array of integers, write a method to find indices m and n such that if you sorted
elements m through n, the entire array would be sorted. Minimize n - m (that is, find the smallest
such sequence).
**EXAMPLE**
Input:1, 2, 4, 7, 10, 11, 7, 12, 6, 7, 16, 18, 19
Output: (3, 9)
17. Contiguous Sequence: You are given an array of integers (both positive and negative). Find the
contiguous sequence with the largest sum. Return the sum.
**EXAMPLE**
Input:2, -8, 3, -2, 4, -10
Output: 5 ( i. e • , { 3, -2, 4})
18. Pattern Matching: You are given two strings, pattern and value. The pattern string consists of
just the letters a and b, describing a pattern within a string. For example, the string catcatgocatgo
matches the pattern aabab (where cat is a and go is b). It also matches patterns like a, ab, and b.
Write a method to determine if value matches pattern.
19. Pond Sizes: You have an integer matrix representing a plot of land, where the value at that location represents the height above sea level. A value of zero indicates water. A pond is a region of
water connected vertically, horizontally, or diagonally. The size of the pond is the total number of
connected water cells. Write a method to compute the sizes of all ponds in the matrix.
**EXAMPLE**
Input:
0 2 1 0
0 1 0 1
1 1 0 1
0 1 0 1
Output: 2, 4, 1 (in any order)
20. T9: On old cell phones, users typed on a numeric keypad and the phone would provide a list of
words that matched these numbers. Each digit mapped to a set of O - 4 letters. Implement an algorithm to return a list of matching words, given a sequence of digits. You are provided a list of valid
words (provided in whatever data structure you'd like). The mapping is shown in the diagram below:
| 1 | 2 (abc) | 3 (def) |
| 4 (ghi) | 5 (jkl) | 6 (mno) |
| 7 (pqrs) | 8 (tuv) | 9 (wxyz) |
| | 0 | |
**EXAMPLE**
Input:
Output:
8733
tree, used
21. Sum Swap: Given two arrays of integers, find a pair of values (one value from each array) that you
can swap to give the two arrays the same sum.
**EXAMPLE**
Input: {4, 1, 2, 1, 1, 2} and {3, 6, 3, 3}
Output: {1, 3}
22. Langton's Ant: An ant is sitting on an infinite grid of white and black squares. It initially faces right.
At each step, it does the following:
(1) At a white square, flip the color of the square, turn 90 degrees right (clockwise), and move forward
one unit.
(2) At a black square, flip the color of the square, turn 90 degrees left (counter-clockwise), and move
forward one unit.
Write a program to simulate the first K moves that the ant makes and print the final board as a grid.
Note that you are not provided with the data structure to represent the grid. This is something you
must design yourself. The only input to your method is K. You should print the final grid and return
nothing. The method signature might be something like void printKMoves (int K).
23. Rand7 from Rands: Implement a method rand7() given rand5( ). That is, given a method that
generates a random number between O and 4 (inclusive), write a method that generates a random
number between O and 6 (inclusive).
24. Pairs with Sum: Design an algorithm to find all pairs of integers within an array which sum to a
specified value.
25. LRU Cache: Design and build a "least recently used" cache, which evicts the least recently used
item. The cache should map from keys to values (allowing you to insert and retrieve a value associated with a particular key) and be initialized with a max size. When it is full, it should evict the least
recently used item.
26. Calculator: Given an arithmetic equation consisting of positive integers, +, -, * and / (no parentheses), compute the result.
**EXAMPLE**
Input: 2*3+5/6*3+15
Output: 23.5

### 17 Hard
1. Add Without Plus: Write a function that adds two numbers. You should not use+ or any arithmetic
operators.
2. Shuffle: Write a method to shuffle a deck of cards. It must be a perfect shuffle-in other words, each
of the 52! permutations of the deck has to be equally likely. Assume that you are given a random
number generator which is perfect.
3. Random Set: Write a method to randomly generate a set of m integers from an array of size n. Each
element must have equal probability of being chosen.
4. Missing Number: An array A contains all the integers from Oto n, except for one number which
is missing. In this problem, we cannot access an entire integer in A with a single operation. The
elements of A are represented in binary, and the only operation we can use to access them is "fetch
the jth bit of A[ i ],"which takes constant time. Write code to find the missing integer. Can you do
it in O(n) time?
5. Letters and Numbers: Given an array filled with letters and numbers, find the longest subarray with
an equal number of letters and numbers.
6. Count of 2s: Write a method to count the number of 2s that appear in all the numbers between O
and n (inclusive).
**EXAMPLE**
Input: 25
Output: 9 (2, 12, 20, 21, 22, 23, 24 and 25. Note that 22 counts for two 2s.)
7. Baby Names: Each year, the government releases a list of the 10000 most common baby names
and their frequencies (the number of babies with that name). The only problem with this is that
some names have multiple spellings. For example, "John" and ''.Jon" are essentially the same name
but would be listed separately in the list. Given two lists, one of names/frequencies and the other
of pairs of equivalent names, write an algorithm to print a new list of the true frequency of each
name. Note that if John and Jon are synonyms, and Jon and Johnny are synonyms, then John and
Johnny are synonyms. (It is both transitive and symmetric.) In the final list, any name can be used
as the "real" name.
**EXAMPLE**
Input:
Names: John (15), Jon (12), Chris (13), Kris (4), Christopher (19)
Synonyms: (Jon, John), (John, Johnny), (Chris, Kris), (Chris, Christopher)
Output: John (27), Kris (36)
8. Circus Tower: A circus is designing a tower routine consisting of people standing atop one another's shoulders. For practical and aesthetic reasons, each person must be both shorter and lighter
than the person below him or her. Given the heights and weights of each person in the circus, write
a method to compute the largest possible number of people in such a tower.
**EXAMPLE**
input(ht,wt): (65, 100) (70, 150) (56, 90) (75, 190) (60, 95) (68, 110)
Output: The longest tower is length 6 and includes from top to bottom:
(56, 90) (60,95) (65,100) (68,110) (70,150) (75,190)
9. Kth Multiple: Design an algorithm to find the kth number such that the only prime factors are 3, 5,
and 7. Note that 3, 5, and 7 do not have to be factors, but it should not have any other prime factors.
For example, the first several multiples would be (in order) 1, 3, 5, 7, 9, 15, 21.
10. Majority Element: A majority element is an element that makes up more than half of the items in
an array. Given a positive integers array, find the majority element. If there is no majority element,
return-1. Do this inO(N) time and 0(1) space.
**EXAMPLE**
Input: 1 2 5 9 5 9 5 5 5
Output: 5
11. Word Distance: You have a large text file containing words. Given any two words, find the shortest
distance (in terms of number of words) between them in the file. If the operation will be repeated
many times for the same file (but different pairs of words), can you optimize your solution?
12. BiNode: Consider a simple data structure called BiNode, which has pointers to two other nodes.

    ```java
    public class BiNode {
      public BiNode nodel, node2;
      public int data;
    }
    ```
     The data structure BiNode could be used to represent both a binary tree (where nodel is the left
    node and node2 is the right node) or a doubly linked list (where node1 is the previous node and
    node2 is the next node). Implement a method to convert a binary search tree (implemented with
    BiNode) into a doubly linked list. The values should be kept in order and the operation should be
    performed in place (that is, on the original data structure).
{:start="13"}
13. Re-Space: Oh, no! You have accidentally removed all spaces, punctuation, and capitalization in a
lengthy document. A sentence like "I reset the computer. It still didn't boot!"
became "iresetthecomputeritstilldidntboot''. You'll deal with the punctuation and capitalization later; right now you need to re-insert the spaces. Most of the words are in a dictionary but
a few are not. Given a dictionary (a list of strings) and the document (a string), design an algorithm
to unconcatenate the document in a way that minimizes the number of unrecognized characters.
**EXAMPLE**:
Input: jesslookedjustliketimherbrother
Output: jess looked just like tim her brother (7 unrecognized characters)
14. Smallest K: Design an algorithm to find the smallest K numbers in an array.
15. Longest Word: Given a list of words, write a program to find the longest word made of other words
in the list.
**EXAMPLE**
input:cat, banana, dog, nana, walk, walker, dogwalker
Output: dogwalker
16. The Masseuse: A popular masseuse receives a sequence of back-to-back appointment requests
and is debating which ones to accept. She needs a 15-minute break between appointments and
therefore she cannot accept any adjacent requests. Given a sequence of back to-back appointment requests (all multiples of 15 minutes, none overlap, and none can be moved), find the optimal
(highest total booked minutes) set the masseuse can honor. Return the number of minutes.
**EXAMPLE**
Input: {30, 15, 60, 75, 45, 15, 15, 45}
Output:180 minutes ({30, 60, 45, 45}).
17. Multi Search: Given a string band an array of smaller strings T, design a method to search b for
each small string in T.
18. Shortest Supersequence: You are given two arrays, one shorter (with all distinct elements) and one
longer. Find the shortest subarray in the longer array that contains all the elements in the shorter
array. The items can appear in any order.
**EXAMPLE**
Input:{1, 5, 9} I {7, 5, 9, 0, 2, 1, 3, 5, 7, 9. 1, 1, 5, 8, 8, 9, 7}
Output: [ 7, 10] (the underlined portion above)
19. Missing Two: You are given an array with all the numbers from 1 to N appearing exactly once,
except for one number that is missing. How can you find the missing number in O(N) time and
0(1) space? What if there were two numbers missing?
20. Continuous Median: Numbers are randomly generated and passed to a method. Write a program
to find and maintain the median value as new values are generated.
21. Volume of Histogram: Imagine a histogram (bar graph). Design an algorithm to compute the
volume of water it could hold if someone poured water across the top. You can assume that each
histogram bar has width 1.
**EXAMPLE** (Black bars are the histogram. Gray is water.)
Input:{0, 0, 4, 0, 0, 6, 0, 0, 3, 0, 5, 0, 1, 0, 0, 0}
Output: 26
22. Word Transformer: Given two words of equal length that are in a dictionary, write a method to
transform one word into another word by changing only one letter at a time. The new word you get
in each step must be in the dictionary.
**EXAMPLE**
Input: DAMP, LIKE
Output: DAMP-> LAMP-> LIMP-> LIME-> LIKE
23. Max Black Square: Imagine you have a square matrix, where each cell (pixel) is either black or white
Design an algorithm to find the maximum subsquare such that all four borders are filled with black
pixels.
24. Max Submatrix: Given an NxN matrix of positive and negative integers, write code to find the
submatrix with the largest possible sum.
25. Word Rectangle: Given a list of millions of words, design an algorithm to create the largest possible
rectangle of letters such that every row forms a word (reading left to right) and every column forms
a word (reading top to bottom). The words need not be chosen consecutively from the list but all
rows must be the same length and all columns must be the same height.
26. Sparse Similarity: The similarity of two documents (each with distinct words) is defined to be the
size of the intersection divided by the size of the union. For example, if the documents consist of
integers, the similarity of { 1, 5, 3} and { 1, 7, 2, 3} is 0. 4, because the intersection has size
2 and the union has size 5.
We have a long list of documents (with distinct values and each with an associated ID) where the
similarity is believed to be "sparse:'That is, any two arbitrarily selected documents are very likely to
have similarity 0. Design an algorithm that returns a list of pairs of document IDs and the associated
similarity.
Print only the pairs with similarity greater than 0. Empty documents should not be printed at all. For
simplicity, you may assume each document is represented as an array of distinct integers.
**EXAMPLE**
Input:
13: {14, 15, 100, 9, 3}
16: {32, 1, 9, 3, 5}
19: {15, 29, 2, 6, 8, 7}
24: {7, 10}
Output:
ID1, ID2 : SIMILARITY
13, 19 : 0.1
13, 16 : 0.25
19, 24 : 0.14285714285714285
***

## 4chan  Challenges

### Ultra Easy Questions:
1. Print out your name on the screen.
2. Count down from 700 to 200 in decrements of 13. (Note: 90% of programming job applicants, and -50% of /g/, will fail here)
3. Sum all the integers from 0 -> 1000. Sum all the integers from [x] -> [y], assuming that "x" is smaller than "y".
4. Let the user input their [name], and check if it is "Jack". If it is "Jack", print out "Hi Jack!". Otherwise, print out "Hello, Enamel".
5. Using the modulus operator, label all the even and odd numbers from 0-100. Do it again without the modulus operator. And a third time without using if/else/switch. (Note: 99.5% of programming job applicants, and 80% of /g/, will fail here)
6. Print the 12x12 multiplication table. (Challenge: Use only a single loop.)
7. Assume that the user will enter a moderately long (10+ words) sentence as input. Split this sentence into words, then display it as one word per line.
8. Generate three random integers, each between 0-20. Find the largest, smallest, and average of the three.
9. For a certain school class, you are given one test and an optional project. For the test, if you score below 50 (out of a 100), you get an F. 50-69 is C, 70-89 is B, and 90-100 is A. If you submit the optional project, you raise your grade by one letter. Let the user input their marks (0-100) and whether they submitted the project (Y/N), and give them their grade.
10. Generate 100 random integers, each between 0-10000. Enter a number and check if it is in the list.
11. Write a program that lets you play "Higher/Lower" vs a computer. Take turns to see who chooses and who guesses.

### Very Easy Questions:
1. Make a standard deck of cards. Shuffle the deck, and draw two cards at random. Display the two cards.
2. You are given an integer in the range of 0-10000, representing time in seconds. Convert it to time in the format of "1-1H:rnm:ss".
3. Flip two coins, and note whether they land as two heads, two tails, or a head and a tail. Do this a thousand times, and display the results as three percentages.
4. After entering an initial amount of money and an interest rate, calculate how much money there will be after [x] years. Assume interest is applied once a year.
5. Generate a list of 200 integers, each between 0-10. Order it by size ascending, then by size descending. Now order it by mode ascending, and mode descending. (Mode is the most frequently repeated number in a list).
6. Use recursion to divide one integer by another, and also show the remainder. Do it again, and this time you must handle negative numbers.
7. Convert a number from a normal base10 integer to Roman numerals.
8. Using only mathematical operations (no toString or similar methods), concatenate two positive integers.
9. The numbers 121 and 123321 are palindromes. Check if positive integer [x] is a palindrome.
10. The sum of all primes below 10 is 2+3+5+7=17. Find the sum of all primes below two million. (Extreme mode: Do this on a whiteboard.)
11. Assume that you are retrieving an array of integers. This array has a size of 1000, and was supposed to be filled with all the unique integers from 0 to 999 in random order. Unfortunately, there was a problem with the person inputting the data, and we do not know if the array is actually full or not. We also know that one of the integers was repeated by mistake, while all the rest were unique. Find the repeated integer.

### Easy Questions:
1. Ignoring whitespace, check if two strings are anagrams.
2. Find all the prime factors of a positive integer entered by the user.
3. Given an integer array of size 10, check if the integers are in ascending order, descending order, or neither.
4. Let the user enter a credit card number. Use Luhn's algorithm to verify that it is valid.
5. Generate a very, very large random number. Check how many digits it has.
6. An array of size 100 is filled with random integers. Let the user pick an integer [x] between 0 and 98. Reverse the order of all the cells from [x] to [99].
7. The coordinates of the centres and radii of two circles are chosen randomly. At what points (if any) do the circles intersect?
8. Write an algorithm that plays the Towers of Hanoi with "n" disks.
9. A mouse-and-cheese maze consists of an array of 100x100 cells. Each cell has 4 doors, which may be locked or unlocked to make the maze. The mouse starts at home in [0][0], the cheese is placed randomly, and the doors to all cells are locked/unlocked to make a maze. Write the algorithm to help the mouse search for the cheese, then guide it back home, assuming that the mouse remembers every room it has been in before. (Hard (easy?) mode: The mouse has short term memory, and only remembers the direction of the room it just came from.)
10. A square-shaped state is divided into 50x50 counties. By law, only one cinema is allowed per county. 20 cinemas have already opened, though their locations were chosen randomly. You want to open your cinema, but you are smart, and will choose a county that is furthest away from the 20 counties with cinemas in them. Write a program to help you solve this.
11. Write a program that lets you play Tic-Tac-Toe vs a computer. Flip a coin to see who goes first. (Extra credit: The computer should never lose )

### Bonus Questions:
1. Simulate a 3x3 "sliding pieces" puzzle. Scramble it randomly for n moves, then let the program solve it.
2. Simulate an 8x8 chess board that has the kings and queens, and no other pieces. While obeying the standard rules of chess, let each piece move in a random direction, until there is a checkmate. If checkmate becomes impossible, declare a draw.
3. Generate a random integer [x] between 2-10. Solve Ultra easy question [x] using enterprise-grade code. (Extreme mode: Do this while someone is watching over your shoulder.)
4. In your programming language of choice, write a program that checks your code for syntax errors.
5. Create a non-trivial UI that the client will like on the first try.
6. Create a time-management program. Use it. For 5 years.
7. Write a program that lets you play Tetris vs a computer.

### Technical Questions
1. What is the difference between a pointer and an address?
2. What is the difference between a structure and a class?
3. What is the difference between a string and a character array?
4. What is the difference between an int and a short?
5. What is the difference between "return by value" and "return by reference"?
6. Name a situation where static variables would be useful.
7. Name a situation where an abstract class would be useful.
8. Name a situation where an unsigned integer would be useful.
9. Name a situation where do/while would work better than while.
10. Name a situation where recursion would be used, other than the Fibonacci sequence.
11. What is "this"? Name a situation where you will need to use "this".
12. What is malloc?
13. What are FIFO and LIFO?
14. What is bubble sort, and what is selection sort?
15. What is operator overloading?
16. What is polymorphism?

### Theory:
1. You are continuously flipping one coin. What series of flips is more likely to come up first: TTH, or THT?
2. Jason says: "If your are being mugged at the ATM, put your PIN in backwards to call the police!" From an ATM-programmer's perspective, could Jason be right? Why/why not?
3. Can you think of a number where adding 2 gives the same result as multiplying the number by itself? Can you think of another number with this exact same property?
4. Townsville has two barbers. Barber John is neat, clean shaven, and looks well groomed. Barber Jack looks dirty, messy, and dishevelled. Where do you go for a haircut?
5. In the country of Logicia, the number of cars is twice what the roads can handle. The President/king decrees that on even numbered days of the month, cars with even-numbered registration plates can drive, and odd-numbered cars on odd-numbered days. Assuming a non-leap year, is this fair?
6. The time is now 12:15. What is the angle between the minute hand and the hour hand? (Hard mode: The time is now 2:35, and you must do the calculations entirely in your head.)
7. You have 8 marbles, identical in size and colour. One of them is very slightly heavier, all the rest weigh the same. What is the minimum number of weighings on a balance-scale that is needed to figure out which marble is the heavy one, with certainty?
8. People are randomly picked from a typical population, and their birthdays noted. Are there any dates or months which you expect to have below/above average rate of birthdays? What is the probability that a random person has their birthday on a specific date (e.g. March 17th)? What is the probability that three random people share the same birthday?
9. The battery of an analogue dock mounted on the wall is almost dead. The second hand is twitching every second, but not moving around. What number is the second hand pointing to?
10. Three adventurous friends are travelling on foot, and have reached the edge of the desert. They want to cross this desert, but do not know how far away the opposite edge of the desert is. There is a lake at the edge of the desert, and it is reasonable to assume that there is a water source on the opposite edge of the desert, too. The party has many water containers with them. Each member of the party can carry 10 litres of water, needs to drink a litre per day, and can walk 10 km per day. The water containers cannot survive being left unattended. While ensuring survival if the opposite edge is not found, how far can the party explore 12 days? 16days? How long would it take to explore 110km, while ensuring survival? With infinite patience and infinite lifespans, can the friends explore forever?
11. You have two genetically modified eggs that are supposed to be unbreakable, but you know that they are breakable if you drop them from high enough. With a building with 100 floors, how do you determine what floor they will break using the least number of steps?
12. Cannibals have captured 4 mathematicians, and will eat them! But these cannibals are sporting, and will give the mathematicians a single chance to save themselves. The cannibals bring a large bag with 7 hats, 4 white, 3 black. Then they tie up the mathematicians very securely in a row. Each mathematician can see what is ahead, but not what is above or behind. A hat is taken from the bag, and placed on each mathematician's head, without that mathematician being able to see it. Since they are in a row, the last mathematician can see the three hats ahead, the next mathematician can see two hats, the next can see one hat, and the mathematician who is first in line can see no hats at all. The rules are simple: Any mathematician who figures out the colour of their hat can say the colour, but saying anything else at all will lead to all four being eaten. If just one mathematician figures out the colour of their hat, all four are free. An hour passes, and no one says a thing. Then another hour. And a third hour of silence. Then, after four hours, the FIRST mathematician in line (who can see nothing) figures it out! What colour was the hat, and how did that mathematician figure it out?
13. You are running a small book store with a membership program, and want to track sales. Name the classes and methods that you would use for this.
14. A spaceship needs to fire a laser to hit another laser being fired from earth, in mid-air. You cannot set a preset/specific time for firing due to cloudy weather, so it is play by ear. Communication is via satellite internet, with a variable -1-3 second communication lag. How do you synchronize the lasers' firing times?
15. People want to play a card game with real-life collectible cards, but online vs players on other continents using webcams. What cheating methods do you foresee? Now would you set up the game/cards/system to be cheat-proof?
16. You are taken prisoner before you can arrange a code with your family. To torture you, you get to choose tomorrow's winning lottery numbers, and you get to email your family, but your email is proofread (and censored if needed) by a bunch of smart people. Now do you get the numbers out?
(Questions 1-12 have optimum/exact answers. Questions 13-14 have multiple comet answers. Questions 15-16 are open ended. Nearly all of these questions come from the internet. Thanks internet)

***

## Pro/g/ramming Challenges, v4.0
### Four degrees of difficulty (Easy) (Medium) (Difficult) (Fuck You)
### Categories:
#### Practical: 1-43, 135-139, 140-144
#### Algorithmic: 44-69, 134
#### Artificial Intelligence: 70-77
#### Compiler/Interpreter/Debugger: 78-90, 133
#### Emulation/Modeling: 91-103, 145
#### Games: 104-132

1. (Medium) Download Manager
2. (Medium) Make an elastic producer/consumer task queue
3. (Medium) IRC Client
4. (Easy) Markov Chain Sentence Generator(Include shitposting capabilities)
5. (Medium) English Sentence Parser that points to the context of a sentence
6. (Medium) MIDI Player + Editor
7. (Medium) Stock Market Simulator Using Yahoo Spreadsheet data
8. (Difficult) Parametric/Graphic Equalizer for .wav files(Make it real-time)
9. (Medium) Graphing Calculator(BONUS: Graph the Function's Derivatives)
10. (Easy) To-Do List Application(Web app or CLI)
11. (Difficult) Verlet Intergration(Verlet Cloth)
12. (Medium) TCP/UDP Chat Server + Client
13. (Difficult) Music Streaming
14. (Medium) Shazam
15. (Easy) Chatbot(with conversation retention)
16. (Medium) Curses Text Editor(with Emacs/Vim keybindings)
17. (Medium) Paint Clone
18. (Easy) Image to ASCII Art
19. (Medium) Booru(image board) Image Downloader
20. (Medium) Image Converter
21. (Medium) ID3 Reader
22. (Difficult) Sound Synthesis(Sine, square, sawtooth, etc...)("Fuck you" mode: Realtime MIDI Playback with Custom Instruments)
23. (Medium) C++ IDE Plugin for Sublime/Atom(Auto-Complete, Go-To Symbol Declaration and Definition using Clang's AST)
24. (Medium) Simple Version Control supporting checkout, commit(with commit message), unlocking, and per-file configuration of number of revisions kept
25. (Easy) Imageboard(imagine vichan)
26. (Medium) Password Manager
27. (Difficult) Create a Torrent Client(CLI or GUI)
28. (Difficult) Booru Client
29. (Medium) Key Press Bot
30. (Medium) IP/URL [Obsucrification](http://www.pc-help.org/obscure.htm)
31. (Medium) Radix Base Converter(Given a radix base, convert it to decimal)
32. (Difficult) Chan aggregator(Let's user view various boards from different 'chans')(Bonus: Add 4ChanX and Archiving Functionality)
33. (Medium) Encrypt a File, and Upload it online
34. (Difficult) Make a TextEditor that autosaves and includes the data in the filename
35. (Easy) Create an HSV Color Representation
36. (Medium) Window Manager
37. (Fuck You) Basic Relation Database Software(SQL Support Handle Relationships, Focus on Efficiency)
38. (Medium) Pixel Editor
39. (Medium) Trivial File Transfer Protocol(TFTP): Allow a client to put a file onto a remote host
40. (Medium) Markdown(HTML/XML) Editor
41. (Medium) IP Tracking Visualization
42. (Easy) Port Scanner
43. (Easy) Old School Demo Effect(Plasma, Tunner, Scrollers, Zoomers, etc...)
44. (Easy) Fizzbuzz(BONUS: In ASSEMBLY)
45. (Easy) RPN Calculator
46. (Easy) Counts occurrences of characters in Given String(Include Support for unicode characters)
47. (Easy) Towers of Hanoi
48. (Medium) Music Visualizer
49. (Medium) Unicode Converter(Support for UTF-8, 16LE, 32LE, and 32BE)
50. (Easy) Calculate the first(n) digits of pi
51. (Medium) Least Squares Fitting Algorithm
52. (Easy) Given an Array of Stock's values over time, find the period of time where the stocks could have made the most money
53. (Easy) highest Prime Factor Calculator
54. (Medium) Hide and Extract Data in Images(Basic Stenography)(Bonus: Include .gif support)
55. (Medium) Web Page Crawler
56. (Easy) Password Generator(let User Choose Options)
57. (Medium) Vigenère cipher encryption/decryption
58. (Medium) Game Of Life
59. (Easy) Ceaser Cipher Cracker
60. (Medium) Dijkstra's Algorithm
61. (Easy) ROT 13
62. (Medium) Program that displays MBR Contents
63. (Medium) Random Name Picker
64. (Easy) Encrypt/Decrypt Text: Implement at least one from [rumkin](http://rumkin.com/tools/cipher/)
65. (Easy) Youtube To MP3
66. (Easy) Text to Hexadecimal/Binary
67. (Medium) Calculate the first 1,000 digits of pi iteratively
68. (Easy) Sierpinski Triangle
69. (Medium) Mandelbrot Set
70. (Difficult) OpenAI Gym Project
71. (Medium) AI for Roguelikes
72. (Medium) Sudoku/n-Puzzle Solver using A' algorithm
73. (Medium) Connect-4 AI Player using Alpha-Beta Prunning
74. (Easy) Basic Neural Network - Simulate individual neurons and their connections
75. (Medium) Real Neural Network - Implement a basic feed-forward neural network using matrices for entire layers along with matrix operations for computations
76. (Medium) Convolutional Neural Network: Implement a convolutional neural network for a handwritten digit recognition, test on MNIST Dataset(Use TensorFlow, Theano, etc...)
77. (Difficult) Convolutional Neural Network: Implement your own convolutional neural network for handwritten digit recognition, test on MNIST Dataset(Without TensorFlow, Theano, etc...)
78. (Medium) Virtual Machine with a Script that writes "Hello, World!"
79. (Fuck You) Basic Bootloader(with extended file system)
80. (Medium) Terminal Shell(Executable Binaries, Pipe System, Redirection, and History)(BONUS: Make it a GUI)
81. (Medium) HTML + JavaScript Debugger
82. (Medium) Write an Interprested LISP-like Programming Language
83. (Difficult) Write an application that is capable of mounting filesystems from other OSes using the FUSE model
84. (Medium) Universal Asynchronous Receiver/Transmitter(UART) Game(in assembly)
85. (Difficult) Pong Game as a UEFI file in color ([Hint](http://rodsbooks.com/efi-programming/index.html))
86. (Difficult) Design an Esoteric Language
87. (Difficult) C Compiler
88. (Difficult) Turing Machine Simulator
89. (Difficult) Read, Evaluate, Print Loop using a compiled langugae
90. (Medium) Static Website Generator(Scriptable Templates + Content -> HTML and CSS)
91. (Medium)Chip - 8 Emulator (Hard Mode: Cached Interprester. Fuck You: Dynamic Recompiler, use dynarec/jit library)
92. (Medium) Double Pendulum Simulation
93. (Medium) Constructive Solid Geometry
94. (Difficult) Ray Tracer
95. (Difficult) Real-Time Fast Fourier Transform Spectrum Visualizer
96. (Easy) Generate a Complimentary Color from any input color
97. (Medium) Generate a 5-Color Scheme from the most dominant tones in any image
98. (Fuck You) General Lambert's-Problem Solver(At least it's not rocket science.. Oh wait it actually is)
99. (Difficult) TI-86 Emulator(Bonus: Include the Option to Create Programs)
100. (Medium) N-Body Simulator, with particles having a certain mass and radius depending on the mass that merge if they collide(Bonus: Include a GUI where you can place particles)
101. (Easy) Eulerian Path
102. (Easy) Draw a spinning 3D Cube
103. (Easy) Cellular Textures
104. (Medium) Knight's Tour
105. (Difficult) Monster Raising/Breeding Simulator
106. (Medium) Tetris
107. (Easy) Snake
108. (Medium) Pipe Dreams
109. (Medium) Pac Man, With Different Behaviors for each ghost
110. (Difficult) Dragon Quest/Basic RPG Engine
111. (Easy) Rock Paper Scissors
112. (Difficult) First-Person Engine in OpenGL(Walking, Looking Around, Jumping on Obstacles)(BONUS: VR Compatibility)
113. (Medium) Shuffle a Deck of Cards
114. (Medium) Simulate a game of Tag using a multi-agent system
115. (Difficult) Wolfenstein Clone(FPS, two-dimentional map that appears to be 3-D)(If you need a starting point, search for [Bisqwit's video](https://www.youtube.com/watch?v=HQYsFshbkYw) about DOOM-like Engines)
116. (Medium) Scorched Earth Clone
117. (Medium) Minesweeper
118. (Medium) An Audio/Visual 64KB Demonstration
119. (Medium) Sudoku
120. (Difficult) Danmaku(Bullet Hell) Engine
121. (Difficult) Roguelike Engine/Dungeon Generator
122. (Easy) Design a Game Engine in Unity
123. (Easy) Yahtzee
124. (Easy) Oil Panic
125. (Medium) Chess
126. (Difficult) Go(No AI Necessary)
127. (Easy) Connect Four
128. (Medium) Mastermind
129. (Medium) Missile Command Game
130. (Medium) Tron
131. (Medium) Breakout
132. (Easy) Simon
133. (Difficult) LIST Interpreter
134. (Easy) Ulam Spiral
135. (Medium) Bellman-Ford Simmulation with at least Five Vertices
136. (Medium) Matrix Arithmetic
137. (Medium) File Compression Utility(Make it GUI)
138. (Easy) PDF Tagger
139. (Difficult) Nonogram Generator and Solver
140. (Medium) Calculate Dot and Cross Product of Two Vectors
141. (Medium) Bismuth Fractal
142. (Medium) Seam Carving
143. (Medium) Bayesian Filter
144. (Difficult) WMS viewer that isn't web based
145. (Easy) ASCII Digital Clock

### HOW-TO Guide

0. **Use git and an external website to push on:**

    Learn to use git and commit early and often. Optionally, use a website to push your work to (such as GitHub). The most important thing is to build a portfolio.

1. **Understand the problem:**

    Do your own research. It's an incredibly useful skill which can be applied to and can be applied to anything else.
    If a problem seems difficult, good! Draw it out, write it out, do whatever you need to do to solve it.
    If the problem you're solving is too easy, brainstorm and try adding additional functionality. Try combining it with other ideas to make your software more challenging.

2. **Implementation:**

    Take the language you're most familiar with to start your project. If the problem is too easy, pick a language you've never used. Don't be afraid to write awful code and don't worry about the best implementation. Get a working implementation first, then refactor and clean it up.

3. **Test:**

    Write test cases for your program. Get used to thinking about how you can break your software. Find problems, bugs, and fix them. Repeat over and over again and document it. Throw it together in your portfolio(don't forget to commit!).

4. **Re-Implement:**

    Now that you have something together with lots of documentation and experience, try a different language and try to match it as closely as possible to your first implementation. Add features, try new techniques, new styles. Go crazy!

5. **Don't stop learning:**

    Now that you've gotten this far, don't stop trying to challenge yourself. Keep a portfolio/blog/diary and keep adding to it.

6. **Resources:**

    {Wikipedia, Stack Overflow, Google}

    Seriously, this is all you'll ever need. If you aren't getting results, you aren't doing your research properly. With these three websites, you'll find your answers. If they don't exist, make a thread. By doing so, you help other people out too!

    Remember: If you make a new topic for a new problem anywhere, write down the solution if someone PM'd you. It helps people a lot and encourages them to do the same.

7. **Literature:**

    *Knuth:* The Art of Computer Programming

    *Siena:* The Algorithm Design Manual

    *Carmen et al:* Introduction to Algorithms

    *Russel:* Artificial Intelligence: A Modern Approach

    *Abel son:* Structure and Interpretation of Computer Programs

8. **Hungry for More?**

    Below is a small list of websites that contain additional Challenges:

  * [HackerRank](https://www.hackerrank.com/)

  * [CodeChef](https://www.codechef.com/)

  * [CofeFights](https://codesignal.com/)

  * [ProjectEuler](https://projecteuler.net/)

  * [RosettaCode](http://rosettacode.org/wiki/Rosetta_Code)

  * [CodeAbbey](https://www.codeabbey.com/)

  * [CodingBat](https://codingbat.com/)

  * [ProgrammingPraxis](https://programmingpraxis.com/)
