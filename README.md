# Search
Searching Algorithms are designed to check for an element or retrieve an element from any data structure where it is stored. They have applications in many computer science applications. Basically, searching algorithms allow the user to find a target element given the list of elements. In fact, we can use two common searching techniques – The Linear Search and Binary Search to find the search target.

## Linear Search
Basically, the Linear search is a technique which allows user to search a particular value from a list of values/ The list of values is available in an array. The searching starts from the beginning of the array. The linear search compares the target value with each value in the array one-by-one and stops when either the target element is found or the search reaches the end of the array.

## Binary Search
Binary search makes the searching process more efficient. Just like the linear search, the objective of the binary search is also to find the target value from a list of values such as an array. In fact, the binary search doesn’t compare the target value with each element of the array. Instead, the binary search works in the following way.  

We compare the target value with the middle element of the array. The binary search returns the index of the target if there is a match. Otherwise, if the target element is less than the middle element, the second half of the array is discarded and the value is again compared with the middle element of the first half of the array. In contrast, if the target value is larger than the middle element, the first half of the array is discarded and the value is compared with the middle element. The binary search repeats this process until either it finds the target element or there is no remaining element in the array.
