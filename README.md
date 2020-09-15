# SELECTION-SORT

 We divide the array into two parts: sorted and unsorted. The left part is sorted subarray and the right part is unsorted subarray. Initially, sorted subarray is empty and unsorted array is the complete given array. 
 ##  or
Selection sort is an algorithm that selects the smallest element from an unsorted list in each iteration and places that element at the beginning of the unsorted list. 
 
# APPROACH FOR SELECTION SORT

1.Set the first element as minimum.

2.Compare minimum with the second element. If the second element is smaller than minimum, assign the second element as minimum.

Compare minimum with the third element. Again, if the third element is smaller, then assign minimum to the third element otherwise do nothing. The process goes on until the last element.

3.After each iteration, minimum is placed in the front of the unsorted list

4.For each iteration, indexing starts from the first unsorted element. They are repeated until all the elements are placed at their correct positions.

# COMPLEXITY: O(n2)

Also, we can analyze the complexity by simply observing the number of loops. There are 2 loops so the complexity is n*n = n2.

## Time Complexities:

# Worst Case Complexity: O(n2)
If we want to sort in ascending order and the array is in descending order then, the worst case occurs.
# Best Case Complexity: O(n2)
It occurs when the array is already sorted
# Average Case Complexity: O(n2)
It occurs when the elements of the array are in jumbled order (neither ascending nor descending).
# 

The time complexity of the selection sort is the same in all cases. At every step, you have to find the minimum element and put it in the right place. The minimum element is not known until the end of the array is not reached.


# Space Complexity:

Space complexity is O(1) because an extra variable temp is used.

# Selection Sort Applications
1.The selection sort is used when:
#
2.small list is to be sorted
#
3.cost of swapping does not matter
#
4.checking of all the elements is compulsory
#
5.cost of writing to a memory matters like in flash memory (number of writes/swaps is O(n) as compared to O(n2) of bubble sort)

# LINK FOR REFERENCE
1.mycodeschool:-
https://www.youtube.com/watch?v=GUDLRan2DWM
