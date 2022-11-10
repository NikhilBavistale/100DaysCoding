Insertion sort is a sorting algorithm that places an unsorted element at its suitable place in each iteration.

Algorithm
    insertionSort(array)
        mark first element as sorted
        for each unsorted element X
         'extract' the element X
        for j <-lastSortedIndexdown to 0
         if current element j > X
            move sorted element to the right by 1
        break loop and insert X here
    end insertionSort
    
    Time Complexity
    Best                O(n)
    Worst               O(n2)
    Average             O(n2)
    Space Complexity    O(1)
    Stability           Yes
    
    
