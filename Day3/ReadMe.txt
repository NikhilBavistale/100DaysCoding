Binary search follows the divide and conquer approach in which the list is divided into two halves, and the item is compared with the middle element of the list.
If the match is found then, the location of the middle element is returned.
Otherwise, we search into either of the halves depending upon the result produced through the match.

Algorithm
Begin with the mid element of the whole array as a search key.
If the value of the search key is equal to the item then return an index of the search key.
Or if the value of the search key is less than the item in the middle of the interval, narrow the interval to the lower half.
Otherwise, narrow it to the upper half.
Repeatedly check from the second point until the value is found or the interval is empty.

Input
{ 2, 3, 4, 10, 40 }
Question search 10
Output
At index 3
