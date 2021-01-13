# Array Shift

## Challenge 
- Write a function that takes an array and a value to be added. Return an array with the new value added.

## Approach
- We will first capture our inputs and find the length of the incoming array. Using that we determine it's midpoint. We then will use a for loop over the first values leading up to the midpoint, copying the values from the old array into the new one. We then assign the middle value as the inputted number. We then continue on to a second for loop to copy the remaining values after the midpoint. At the very end, we return the new array when finished.

## Solution
![Whiteboard image](/assets/whiteboard-day2.jpg)