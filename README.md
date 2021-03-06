# Sorting-Algorithms-Performance
CSC 382 - Analysis of Algorithms  
**The performance data of the algorithms can be found in data.pdf**

Programming Assignment: You need to implement insertion sort, merge sort, heap sort, quick sort, and randomized quick sort (increasing or decreasing order) algorithms and measure the performance of these algorithms in terms of number of steps and CPU running time.

For each algorithm, and for each n = 100, 200, 300, 400, 500, 1000, 4000, 10000, measure its running time and number of steps when the input is (1) already sort, i.e. n, n-1, …, 3, 2,1; (2) reversely sorted 1, 2, 3, … n; (3) random permutation of 1, 2, …, n; (4) 50 instances of n random numbers generated in the range of [1..n].

Note:

1. You may have to repeat the algorithm many times, each time you need to initialize the array.

2. Your running time should exclude the time for initialization. 

3. All measurement should be done in a single run, i.e. you do not need to run once for n=100, another time for n=200, etc

What to turn in:

1. Well documented source code in C++

2. Report the number of steps and the CPU running time in a table,

3. Plot the running time of the algorithm results

4. Approximation the constant c in the complexity of insertion sort, merge sort, heap sort, and randomized quick sort by inspecting the results
