# Coursera: Introduction to Embedded Systems Software and Developing Environments

## University of Colorado Boulder

### Week 1 

written a couple of functions that analyze an array of unsigned char data items and report analytics on the `maximum`, `minimum`, `mean`, and `median` of the data set

1. stats.c - Implementation file for your C-programming code
2. stats.h - Header file for your C-programming code


I have written eight functions in the stats.c implemented in the file:

1. `main()` - The main entry point for your program
2. `print_statistics()` - A function that prints the statistics of an array including minimum, maximum, mean, and median.
3. `print_array()` - Given an array of data and a length, prints the array to the screen
4. `find_median()` - Given an array of data and a length, returns the median value
5. `find_mean()` - Given an array of data and a length, returns the mean
6. `find_maximum()` - Given an array of data and a length, returns the maximum
7. `find_minimum()` - Given an array of data and a length, returns the minimum
8. `sort_array()` - Given an array of data and a length, sorts the array from largest to smallest. (The zeroth Element should be the largest value, and the last element (n-1) should be the smallest value. )

## Output:

```c
The original array:

 34  201  190  154    8  194    2    6
114   88   45   76  123   87   25   23
200  122  150   90   92   87  177  244
201    6   12   60    8    2    5   67
  7   87  250  230   99    3  100   90

The Sorted array:
  2    2    3    5    6    6    7    8
  8   12   23   25   34   45   60   67
 76   87   87   87   88   90   90   92
 99  100  114  122  123  150  154  177
190  194  200  201  201  230  244  250

The Median is: 87
The Mean is: 93
The Max is: 250
The Min is: 2
```

