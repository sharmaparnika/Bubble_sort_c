# Bubble Sort 

Bubble sort is a sorting algorithm that works by repeatedly stepping through lists that need to be sorted, comparing each pair of adjacent items and swapping them if they are in the wrong order. This passing procedure is repeated until no swaps are required, indicating that the list is sorted.

It is called bubble sort because the movement of array elements is just like the movement of air bubbles in the water. Bubbles in water rise up to the surface; similarly, the array elements in bubble sort move to the end in each iteration.

### -> Algorithm

In the algorithm given below, suppose arr is an array of n elements. The assumed swap function in the algorithm will swap the values of given array elements.

    begin BubbleSort(arr)  
     for all array elements  
      if arr[i] > arr[i+1]  
         swap(arr[i], arr[i+1])  
      end if  
     end for     
    return arr     
    end BubbleSort  

### -> Bubble Sort Complexity

Now, let's see the time complexity of bubble sort in the best case, average case, and worst case. We will also see the space complexity of bubble sort.

1. Time Complexity

      | Case | Time Complexity |
      | --- | --- |
      | `Best Case` | **O(n)** |
      | `Average Case` | **O(n<sup>2</sup>)** |
      | `Worst Case` | **O(n<sup>2</sup>)** |

*  Best Case Complexity - It occurs when there is no sorting required, i.e. the array is already sorted. The best-case time complexity of bubble sort is O(n).
*  Average Case Complexity - It occurs when the array elements are in jumbled order that is not properly ascending and not properly descending. The average case time complexity of bubble sort is O(n2).
*  Worst Case Complexity - It occurs when the array elements are required to be sorted in reverse order. That means suppose you have to sort the array elements in ascending order, but its elements are in descending order. The worst-case time complexity of bubble sort is O(n2).

2. Space Complexity

      | Space Complexity | 0(1) |
      | --- | --- |
      | `Stable` | **Yes** |

*   The space complexity of bubble sort is O(1). It is because, in bubble sort, an extra variable is required for swapping.
*   The space complexity of optimized bubble sort is O(2). It is because two extra variables are required in optimized bubble sort.

Output:



![image](https://user-images.githubusercontent.com/73773202/150775213-8a528102-11ea-4ec5-8d96-6ab523e53477.png)


---

