Sorting Algorithm Benchmark

This C program benchmarks the runtime and memory usage of Heap Sort and Merge Sort algorithms on different datasets. It reads input data from files, performs sorting using both algorithms, and prints the results.
Table of Contents

Getting Started
Prerequisites

    C compiler (e.g., GCC)
    Standard C libraries
    Input data files (e.g., input1.txt, input2.txt, input3.txt, input4.txt)

Compiling the Program

Compile the program using a C compiler. For example, with GCC:

bash

gcc sorting_benchmark.c -o sorting_benchmark

Usage

bash

./sorting_benchmark

Input Data

The program reads input data from files named input1.txt, input2.txt, input3.txt, and input4.txt. The format of each file is as follows:

Output

The program outputs the runtime and extra memory allocated for both Heap Sort and Merge Sort on each dataset. It also prints the first and last 100 items in the sorted array.
Algorithms
Heap Sort

Heap Sort is a comparison-based sorting algorithm that uses a binary heap data structure to build a max-heap and repeatedly extracts the maximum element.
Merge Sort

Merge Sort is a divide-and-conquer algorithm that divides the array into two halves, recursively sorts each half, and then merges the sorted halves.
File Structure

