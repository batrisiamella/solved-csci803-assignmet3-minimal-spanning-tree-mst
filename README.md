Download Link: https://assignmentchef.com/product/solved-csci803-assignmet3-minimal-spanning-tree-mst
<br>
<ul>

 <li>Design and implement a program based on a greedy algorithm to solve the Minimal Spanning Tree (MST) problem;</li>

 <li>Choose and implement appropriate data structures for the algorithm;</li>

 <li>Analyse the efficiency of different implementations of the algorithm in comparison with the brute force algorithm.</li>

</ul>




<h1>Task</h1>

You should write a single program which implements Prim’s algorithm with different data structures, as well as the brute force search algorithm, to find the MST of an undirected, connected, weighted graph.




<h1>Program</h1>

Your program should read a symmetric matrix from a text file that describes weighted edges of an undirected, connected graph and find the MST that is saved in an output file as a sequence of edges of the MST. The program also displays the numbers of vertices and edges in the graph and the time spent to find its MST for each data structure used in Prim’s and the brute force search algorithms, which can be saved in another output file as well for your later analysis.

Your program should only measure the time spent by the algorithm with its data structure to find the MST so that it is a proper design to use one method/function to implement an algorithm and its associated data structure. For an algorithm that operates on a weight matrix, it takes the weight matrix stored in a two-dimensional array as its parameter; for an algorithm that operates on adjacency lists, it takes adjacency lists you created from the weight matrix.  You may create your own list data structures based on arrays. No STL or Java Collection or other collection framework can be used. In the part of the algorithm implementation, you should not use any library functions including maximal or minimal functions but create your own functions to operate on arrays.

Your program should be readable and well commented.

In addition, you needs to create a small program or script to generate the weight matrix for a graph of various vertices and edges, saved to a text file. When you create graphs, you need consider the density and connectivity of graphs. You may use a program/script by other people, with reference to the source, to generate these matrices.

<h1>Data Structures and Algorithms</h1>

<ul>

 <li>Brute force search algorithm</li>

</ul>

The algorithm operates on a two-dimensional array that represents the weight matrix.




<ul>

 <li>Prim’s algorithm</li>

</ul>

The algorithm operates on one of the following data structures:

<ol>

 <li>two-dimensional array that represents the weight matrix and unordered arrays;</li>

 <li>adjacency lists and heaps.</li>

</ol>




<h1>Requirements</h1>

<ol>

 <li>Program</li>

</ol>

You have two choices on how to write your code.

o Implement the brute force search algorithm and Prim’s algorithm operating on one data structure of your choice;

or  o Integrate the brute force search algorithm and Prim’s algorithm operating on one data structure of your choice. In this case, you may use code available in public domains.

Properly cite the sources of your code in your report and program.




<ol start="2">

 <li>Report

  <ol>

   <li>Cover page</li>

  </ol></li>

</ol>

Student name

Subject code

Student number Email ID

(0 mark; your assignment will not be marked if there is not this section)

<ol>

 <li>Introduction (around 100 words)</li>

</ol>

Describe an application scenario where the MST is applied and the background and purpose of your experiments.  Cite at least one reference.




<ol>

 <li>Methods (around 200 words)</li>

</ol>

Describe algorithms you used in your experiments and data you used to produce the

results.

<ol>

 <li>Result analysis (no more than 500 words)</li>

</ol>

Analyse and discuss your results with reference to time complexity of relevant algorithms (cite the sources). You need to produce results with substantial differences in time spent for each algorithm and data structure. You should use at least one plot to present the results in terms of time spent and graph sizes.

<ol>

 <li>Conclusion (around 50 words)</li>

</ol>

Summarise your findings and interpretations.

(0 mark; -1 mark if there is not this section) f. References

(0 mark; -1 mark if there is not this section; -0.5 marks for each improper reference)




<ol>

 <li>Program</li>

</ol>

Implement the brute force search algorithm and Prim’s algorithm operating on two data structures: matrix and heaps.

<ol start="2">

 <li>Report</li>

 <li>Cover page</li>

</ol>

Student name

Subject code

Student number Email ID

(0 mark; your assignment will not be marked if there is not this section) b. Introduction  (around 200 words)

Describe application scenarios where the MST is applied and identify one application as the background and purpose of your experiments. You should interpret well the meanings of the vertices and edge weights, and why it is an MST problem in your

identified application.  Cite at least three references.                                         c. Methods (around 300 words)

Describe algorithms you used in your experiments and data you used to produce the results.

<ol>

 <li>Result analysis (no more than 600 words)</li>

</ol>

Analyse the time complexity of your algorithms and discuss your results. You need to produce results with substantial differences in time spent for each algorithm and data structure. You should use at least one plot to present the results in terms of time spent and graph sizes.                                                                                         e. Conclusion (around 50 words)

Summarise your findings and interpretations.

(0 mark; -1 mark if there is not this section) f. References

(0 mark; -1 mark if there is not this section; -0.5 marks for each improper reference)


