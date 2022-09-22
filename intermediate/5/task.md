Write a program that automatically generates essays for you. 
1. Using a sample text, create a directed (multi-)graph where the words of a text are nodes and there is a directed edge between u and v if u is followed by v in your sample text. Multiple occurrences lead to multiple edges.
2. Do a random walk on this graph: Starting from an arbitrary node choose a random successor. If no successor exists, choose another random node.
