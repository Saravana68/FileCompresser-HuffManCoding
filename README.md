# FileCompressor-HuffManCoding

<a href="https://saravana-filecompresser.netlify.app/" target="_blank" > Live-Demo </a>
<h1 > Huffman Zipper</h1>
<h3 > File compressor/decompressor, using a Javascript Huffman-coding algorithm implementation.</h3>
<hr>

## Huffman Coding Algorithm Description

Huffman's algorithm assumes that we're building a single tree from a group (or forest) of trees. 
Initially, all the trees have a single node with a character and the character's weight. 
Trees are combined by picking two trees, and making a new tree from the two trees. 
This decreases the number of trees by one at each step since two trees are combined into one tree.

### Algorithm Steps:

1. Begin with a forest of trees. All trees are one node, with the weight of the tree equal to the weight of the character in the node. 
Characters that occur most frequently have the highest weights. Characters that occur least frequently have the smallest weights.
Repeat this step until there is only one tree.

2. Choose two trees with the smallest weights, call these trees T1 and T2. Create a new tree whose root has a weight equal to the sum of the weights T1 + T2 and whose left subtree is T1 and whose right subtree is T2.

3. The single tree left after the previous step is an optimal encoding tree.


# Project Images 
<hr>
  
```bash
  PROJECT - web-View
  ```
                   
  
<img src="https://user-images.githubusercontent.com/63772127/143257340-2a34665b-6df6-44b6-a5ba-4af53b1dec6d.png">

```bash
   PROJECT - MOBILE-VIEW
 ```
<p align="center"> <img src="https://user-images.githubusercontent.com/63772127/143259414-d71e9511-43d9-48f8-90d0-c56cdefae4c7.png"> </p>

```bash
   SAMPLE INPUT & SAMPLE_ENCODED OUPUT 
 ```
 <img src="https://user-images.githubusercontent.com/63772127/143257650-bfb62453-950c-4498-bfb9-f1dbc58e0f3e.png">
 <img src="https://user-images.githubusercontent.com/63772127/143257823-39efd18f-5542-49f9-b950-f649b3b3e7f9.png">

<h3 align='center'> Made with :heart: by Saravanakumar</h3>
