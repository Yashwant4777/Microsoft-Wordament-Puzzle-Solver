# Microsoft-Wordament-Puzzle-Solver
Being a Microsoft Wordament puzzle enthusiact i always wanted to score the maximum points but in the given limit of time couldn't solve it so to over come this i designed an interface which takes the wordament puzzle as input and prints all the valid words which can be formed by that puzzle within seconds.

# How It Works
First the Puzzle grid is taken as input then all the words which exists in the puzzle are formed and then searched in the trie which we build using 58,800 valid words, these words are then compared with the words in the trie and if found then printed.

#Input:- Wordament Puzzle.
#Output:- All valid words.
#Complexity:- O(m) for searching the words in trie (where m=length of word).

![](images/Screenshot(57).png)
