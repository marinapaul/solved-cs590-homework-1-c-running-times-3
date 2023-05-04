Download Link: https://assignmentchef.com/product/solved-cs590-homework-1-c-running-times-3
<br>
<strong>CS590 homework 1 – C++ &amp; running times </strong>

You are given an integer vector which is represented by <em>int* </em>an array of integers and its dimension <em>n</em> as a separate parameter. We are interested in sorting arrays of integer vectors according to a pre-defined notion of vector length. You therefore are given the function <em>ivector_length(v, n)</em> that computes and returns the length of vector <em>v</em> with dimension <em>n</em> as




You are given a naive (and very inefficient) implementation of insertion sort for arrays of integer vectors.







<strong>Questions (100 points) </strong>




<ol>

 <li>Develop an improved implementation of insertion sort for integer vector (<em>insertion_sort_im</em>) that precomputes the length of each vector before the sorting. Keep in mind that the vectors are sorted according to their length (see <em>ivector_length</em> function). You can test the correctness of your sorting algorithm using the provided <em>check_sorted</em></li>

</ol>




<ol start="2">

 <li>Implement a merge sort for an array of integer vectors. As for the improved insertion sort algorithm, you should precompute the length of the vectors before the sorting and the sorting is done according to the vector length. Test the correctness of your merge sort implementation using the provided <em>check_sorted</em></li>

</ol>




<ol start="3">

 <li>Measure the runtime performance of insertion sort (naive and improved) and merge sort for random, sorted, and inverse sorted inputs of size <em>m</em> = 10000; 25000; 50000; 100000; 250000; 500000; 1000000; 2500000 and vector dimension <em>n</em> = 10; 25; 50. You can use the provided functions <em>create_random_ivector</em>, <em>create_sorted_ivector, create reverse_sorted_ivector.</em></li>

</ol>

Repeat each test a number of times (usually at least 10 times) and compute the average running time for each combination of algorithm, input, size <em>m</em>, and vector dimension <em>n</em>. Report and comment on your results.




Remarks:

<ul>

 <li>You are not allowed to use code from online resources. Your submission will be tested against that, and will receive a 0, and a report to the Graduate Academic Integrity Board if it is detected.</li>

 <li>Your report has to be typed, and submitted in a pdf file. You should provide figures that plot the running times in relation to the input size parameters.</li>

 <li>You might have to adjust the value for <em>n</em> depending on your computers speed, but allow each test to take up to a couple of minutes.</li>

 <li>Start with smaller values of <em>n</em> and <em>m</em> and stop if one instance of the algorithm takes more than 5 min to complete (the insertion sort implementations will hit that limit early on).</li>

 <li>Report and comment means that you have to analyze and interpret your findings properly. What do the experiments tell you?</li>

 <li>The programming, testing and the experimentation will take some time. Start early.</li>

 <li>Feel free to use the provided source code for your implementation. You have to document your code.</li>

 <li>A Makefile is provided to build the code in the Virtual Box provided.</li>

 <li>Your code has to compile, and run at the Virtual box shared with you in order to be graded.</li>

 <li>Your methods should be added in the sort.h/sort.cpp files. You must keep the same file structure, makefile that is provided in the skeleton code.</li>

</ul>