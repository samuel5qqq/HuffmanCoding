# HuffmanCoding
Implement huffman code algorithm for loseless data compression.

Visualisation of the use of Huffman coding to encode the message 
<p align="Left">
  <img src="https://upload.wikimedia.org/wikipedia/commons/a/a0/Huffman_coding_visualisation.svg" width = 500>
</p>

## Huffman Coding Algorithm
Step 1: All the nodes are set to be free nodes.</br>
Step 2: The two free nodes with the lowest weights (lowest frequency) are located.</br>
Step 3: Create a parent node, whose weight is the sum of these two child nodes.</br>
Step 4: Let the newly created parent node be a free node and the two child nodes be removed from the free-node list.</br>
Step 5: Assign 0,1 to branches connecting the parent to the two child nodes, respectively.</br>
Step 6: Repeat Step 2-5 until only one free node is left. Denote this node as the root.</br>

## Sample Test
Input:
A15
B7
C6
D6
E5
BDCEA

Output:
A 0
B 100
C 101
D 110
E 111

10011010111
