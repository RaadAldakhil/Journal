# Coding Challenges

##Cracking the coding interview


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
