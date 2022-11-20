# Swinging Monkey

Consider a sequence of n trees { T0, T1, T2, T3, ..., Tn }. From T0, a monkey can swing to the next adjacent tree (T1). It can also swing to other succeeding trees (T2 or T3 or ...) provided that the trees in the middle are shorter than both T0 and the target tree. Suppose that tree heights = 10, 15, and 20 feet. The following are possible pairs of trees that the monkey can swing

## Requirements

1. The program must at least
- 1.1 Get number of trees (at least 3) and the height of each tree from user
- 1.2 Given the tree arrangement in (1.1), report all possible tree-pairs and the total number of pairs
2. Design a better user interface by yourself. Good user interface doesn’t mean fancy output, but rather how your program is easy to understand & to use even without user manual.
3. There are many approaches to solving this problem. Using brute force (i.e. trying all possible states of all lights) is one of them. But you should research and implement a better solution, solving it
with stack or queue and using proper Java collection APIs. Recursive methods are also counted as using stack implicitly.
4. Algorithm to find and count all tree-pairs
- 4.1 How do you check & keep a valid tree-pair and move on to the next pair ? Do not repeat the instructions I gave, but explain the actual calculation/processing
- 4.2 How do you skip invalid tree-pairs ?
- 4.3 Demonstrate how your algorithm works step-by-step until all pairs are found, using the example of 5 trees (19, 17, 15, 20, 20 ft). Show the states of your data structures in each step. Use pictures/diagrams to elaborate your example.
5. Exception handling on convenient limitation. For example, don’t give a limitation that your program will crash if the tree height is negative just because you are too lazy to check for valid input.

## Report

- More informations about our program can be found in the file [SwingingMonkey_Report.pdf](https://github.com/nnichar/SwingingMonkey/blob/main/SwingingMonkey_Report.pdf)

## Authors

- [etnk125](https://github.com/etnk125)
- [nnichar](https://github.com/nnichar)
- BillyFragfart
