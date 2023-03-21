# LC2348
Question-:Given an integer array nums, return the number of subarrays filled with 0.

A subarray is a contiguous non-empty sequence of elements within an array.

Solution-:
This is my implementation of the algorithm to count the number of subarrays filled with 0 in a given integer array. To solve this problem, I use a variable count to keep track of the number of zeros encountered so far and a variable ans to keep track of the number of subarrays filled with 0.

I initialize the count and ans variables to 0 and then iterate through the input array using a for loop. For each element in the array, I check if the count is 0 and the current element is 0. If so, I increment the count by 1. If the count is not 0 and the current element is 0, I increment the count by 1. If the count is not 0 and the current element is not 0, I calculate the number of subarrays that can be formed using the current count value and add it to the ans variable. I then reset the count variable to 0.

After the loop, if the count variable is not 0, I calculate the number of subarrays that can be formed using the final count value and add it to the ans variable.

Finally, I return the ans variable as the result of the function
