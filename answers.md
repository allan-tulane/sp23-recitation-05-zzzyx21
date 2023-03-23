# CMPS 2200 Reciation 5
## Answers

**Name:**_______Kyra Zhu__________________


Place all written answers from `recitation-06.md` here for easier grading.







- **1b.**
|    n |   ssort |   qsort-fixed-pivot |   qsort-random-pivot |   tim_sort |
|------|---------|---------------------|----------------------|------------|
|  100 |   0.355 |               0.001 |                0.010 |      0.005 |
|  200 |   1.185 |               0.000 |                0.005 |      0.005 |
|  300 |   2.170 |               0.001 |                0.006 |      0.006 |
|  400 |   3.998 |               0.000 |                0.008 |      0.007 |
|  500 |   6.571 |               0.001 |                0.010 |      0.010 |
|  600 |   8.996 |               0.001 |                0.011 |      0.012 |
|  700 |  11.647 |               0.001 |                0.011 |      0.012 |
|  800 |  66.797 |               0.001 |                0.012 |      0.018 |
|  900 |  21.584 |               0.002 |                0.009 |      0.018 |
| 1000 |  79.385 |               0.001 |                0.013 |      0.021 |



- **1c.**
  qsort-fixed-pivot is the fastest algorithms among all these algorithms for n sizes above. Theoretically, tim-sort should be the fastest algorithms. However, depending on the input size, qsort-fixed-pivot would run faster under this situation of small sizes. Quicksort is faster than merge sort or tim sort for small input size. If the input size is small enough and input data has the pattern that favors quicksort like this, qsort-fixed-pivot would be faster.