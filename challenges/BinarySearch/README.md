# Binary Search

## Challenge
- Write out a function which takes 2 parameters (sorted array & search key), return index of the array that is = to search key or -1 if element. Note: Algorithm should be a binary search.

## Approach 
-Take in sorted array and search value 
- Determine length of the incoming array 
- Determine the index of the midpoint 
- Capture the value of the midpoint 
- Compare midpoint to search value 
- If the search value is less than the midpoint find the midpoint between the beginning of the array and the original midpoint. 
- If the search value is greater than the midpoint, find the midpoint between the original midpoint and the end of the array. 
- Repeat process until value is found, or the whole array has been searched. 
- If value is found return index of value 
- If value is not found return -1 


## Solution

![Whiteboard image](/assets/whiteboard-day3.jpg)
