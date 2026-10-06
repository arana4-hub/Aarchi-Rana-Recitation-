# CMPS 2200 Recitation 01
## Answers

**Name:**_________________________
**Name:**_________________________


Place all written answers from `recitation-01.md` here for easier grading.

- **4) (1 pts)** Describe the worst case input value of `key` for `linear_search`? for `binary_search`? 

    When the "Key" isn't in the list at all. 

- **5) (1 pts)** Describe the best case input value of `key` for `linear_search`? for `binary_search`? 

    When the "key" is in the first element --> fastest result (because it was found in the first check). 

- **8) (1 pts)** Call `print_results(compare_search())` and paste the results here:

>>> print_results(compare_search())
|        n |   linear |   binary |
|----------|----------|----------|
|       10 |    0.017 |    0.059 |
|      100 |    0.008 |    0.007 |
|     1000 |    0.077 |    0.014 |
|    10000 |    0.767 |    0.018 |
|   100000 |    7.218 |    0.053 |
|  1000000 |   41.640 |    0.016 |
| 10000000 |  462.367 |    0.025 |
>>> 


- **9) (1 pts)** Do the theoretical running times match your empirical results?

Yes, the larger the n, the more it grows. 

- **10a) (1 pts)** What is worst-case complexity of searching a list of $n$ elements $k$ times using linear search? 

Searching K times with a linear search. (each k seach is O(kn))

- **10b) (1 pts)** For binary search? 

List is already sorted (each k search is O(klogn))

- **10c) (1 pts)** For what values of $k$ is it more efficient to first sort and then use binary search versus just using linear search without sorting? You may assume that your sorting algorithm runs in $O(n \lg n)$ time.

Sorting first pays when k is larger than logn. For a smaller k, linear --> faster.

   