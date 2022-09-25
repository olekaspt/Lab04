# Lab04

##Objective:
The objective of this homework is to investigate different sorting algorithms.

##Scenario:
In this assignment, we are going to be investigating the actual performance of different sorting methods.  This needs to be written using C++.

##Requirements:
1.	Create a program that generate an array of sizes n= 10, 100, 500, 5000 and 25000 items.  Your program should populate those arrays with randomly generated integers with a value between 0 and the 2n where n is the size of the array.  Create an implementation for the following sort operations.
  a.	Bubble sort
  b.	Insertion sort
  c.	Merge-sort
  d.	Quicksort
  e.	Radix-sort // you probably want to consider storing the values as strings
2.	Test each of the sort operations and record the time the sort takes to complete.  You should test each on the same unsorted array to get the best comparison.  You should do this for each array size (from requirement 1) a minimum of 10 times.  Your test should use the chrono library’s high_resolution_clock class.  The following example of how to do this in nanoseconds is found on Stack Overflow.  Only the time in the 5 sort functions should be measured.
