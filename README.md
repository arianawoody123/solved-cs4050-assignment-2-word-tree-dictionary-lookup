Download Link: https://assignmentchef.com/product/solved-cs4050-assignment-2-word-tree-dictionary-lookup
<br>
For this assignment, you are to write a program to do text prediction

/ suggestion (like Google does when you start typing a search term). That is, as the user types, the program will show a list of N words that the user might be in the process of typing. This assignment requires two phases. The first phase will read in a file with words and build an internal representation as described below. The second phase will use this representation to make text predictions.

Phase1: The internal representation that you are to use is a tree with a branching factor of 26, one branch for each possible letter. Each node should also signify if ending in that node represents a word. For instance, given the string ”parrot”, following a path from the root should end in a node that signifies that a word has occurred. Following a path for the string ”subantiq” should arrive at a node that signifies that a word does not end at that node.

Phase2: Once the tree has been built the program should be ready for user interaction. As the user types, the program should print out about 10 possibilities. If you are using the command line for your program then just print any 10 of the remaining possibilities after each keystroke. If you are using a GUI, then print to a textArea in the GUI.