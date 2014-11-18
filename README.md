String
======
Reverse Words in a String

One simple approach is a two-pass solution: First pass to split the string by spaces into an array of words, then second pass to extract the words in reversed order.

We can do better in one-pass. While iterating the string in reverse order, we keep track of a word’s begin and end position. When we are at the beginning of a word, we append it.

String to Integer (atoi)

To deal with overflow, inspect the current number before multiplication. If the current number is greater than 214748364, we know it is going to overflow. On the other hand, if the current number is equal to 214748364, we know that it will overflow only when the current digit is greater than or equal to 8.
