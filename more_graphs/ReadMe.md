## Getting Started
1.  This folder runs the Shortest path and Cheapest Path algorithms. Depth First Search and Breadth First Search are also implemented but can not be run. See the File [DirectedGraph.java]
in the GraphPackage directory. See Notes below.

2.  To run the algorithm run the [GraphTests.java] file in the [test] directory. If on vscode, press the play button in the top left corner while in the fiel [GraphTests.java].

3. The file **inputFile.txt** is used to run the algorithms, you can use a different file so long as it has the same structure as the one in inputFile.txt. The input file must be in the `more_graphs` directory.

### NOTES:
1. More_graphs: The sudo code and code I didn't write are from the book: Data Structures and Abstraction with Java by Frank Carrano and Timothy Henry.
        With exception to the DirectedGraph.java file in the `GraphPackage`, most code in that package is from the books website. Similary, most of the code in the `ListPackage` is also provided by the book. In both `GraphPackage` and `ListPackage` I had to modify the code to use the `Java.util` library as the code provided by the book uses their own library which I didn't want to use the book's library as it is spread out through out the book. All the Code in the `test` directory was writen by me. The algorithms `Shortest path` and `Cheapest path` were written by me, although the book does provide the implimantation for Shortest Path but NOT Cheapest path.