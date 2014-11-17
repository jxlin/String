String
======
Reverse Words in a String

One simple approach is a two-pass solution: First pass to split the string by spaces into an array of words, then second pass to extract the words in reversed order.

We can do better in one-pass. While iterating the string in reverse order, we keep track of a word’s begin and end position. When we are at the beginning of a word, we append it.
