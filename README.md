# File_Compressor
Data compression is one of the most important areas in computer science. The purpose of this project is to compress a text file and decompress back to original form without any loss of data.
Huffman Encoding is an algorithm which uses frequency features of symbols and a binary tree structure. It consists of the following 3 steps:
● Probability Calculation & Ordering the Symbols
● Binary Tree Transformation
● Assigning Codes to the Symbols
We count the number of each symbol in the whole data, then we calculate the “probability” of each symbol by dividing that count by the total number of characters in the data. Since it's an algorithm using probability, more common symbols — the symbols having higher probability — are generally represented using fewer bits than less
common symbols. This is one of the advantageous sides of Huffman Encoding.
