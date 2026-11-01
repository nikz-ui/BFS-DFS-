File System Representation and Search Using BFS and DFS

Objective

To represent a file system as a graph using an adjacency matrix and search for files using BFS and DFS algorithms.

Algorithms

BFS (Breadth-First Search)

Start from the given node.
Add it to the queue.
Visit adjacent unvisited nodes.
Repeat until the queue is empty.
Display whether the file is found.
DFS (Depth-First Search)

Start from the given node.
Mark it as visited.
Visit adjacent unvisited nodes recursively.
Continue until all reachable nodes are visited.
Display whether the file is found.
How to Run

Compile the program:
gcc file_search.c -o file_search

Run the program:
./file_search

Enter the node names, adjacency matrix, starting node index, and target file name.
Sample Output

BFS Traversal: Root Docs Images a.txt b.pdf photo.jpg File found using BFS.

DFS Traversal: Root Docs a.txt b.pdf Images photo.jpg File found using DFS.

Conclusion

This project demonstrates graph representation and file searching using BFS and DFS in C.

Files

"file_search.c" – C program
"README.md" – Project description
"sample_output.txt" – Sample output
