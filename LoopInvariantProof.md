## Loop Invariant Proof

**3.1 Description of Loop Invariant Technique:**

- The loop invariant technique is a proof method used to demonstrate the correctness of iterative algorithms, particularly those involving loops. It involves identifying an assertion (the loop invariant) that remains true before and after each iteration of the loop. By establishing three key properties – initialization, maintenance, and termination – the loop invariant technique helps demonstrate that the algorithm achieves its intended purpose and terminates correctly.

**3.2 Identification of Loop Invariant:**

-  The loop invariant for the merge() function in the merge sort algorithm is; at each iteration of the merge () function's loop, the subarray being merged is sorted.

**3.3 Initialization Step:**

-  In the initialization step, we need to demonstrate that the loop invariant holds true before the first iteration of the loop. For the merge() function:
- Before the loop begins, the subarrays to be merged consist of single elements, and single-element arrays are trivially sorted. Therefore, the loop invariant holds true initially.

**3.4 Maintenance Step:**

- In the maintenance step, we assume that the loop invariant holds true before an iteration of the loop and demonstrate that it still holds true after executing the iteration. For the merge() function:
- During each iteration, two sorted subarrays are merged into a single sorted subarray. This merging process maintains the sorted order within the merged subarray. Therefore, if the subarrays being merged are sorted before the iteration, the merged subarray will also be sorted after the iteration.

**3.5 Termination Step:**

In the termination step, we show that the loop terminates correctly and that the desired result is achieved. For the merge() function:
- The loop terminates when the merging process is complete, i.e., when all subarrays have been merged into a single sorted array. At this point, the entire array is sorted, fulfilling the goal of the merge sort algorithm. Thus, the termination condition ensures that the loop invariant holds true at the end of the function execution.


```python

```
