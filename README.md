# Sona ulaşmak için minimum atlama sayısı
### Minimum-number-of-jumps-to-reach-end
have the function arraychallenge(arr) take the array of integers stored in arr, where each integer represents the maximum number of
steps that can be made from that position, and determine the least amount of jumps that can be made to reach the end of the array.
for example: if arr is [1, 5, 4, 6, 9, 3, 0, 0, 1, 3] then your program should output the number 3 because you can reach the end of 
the array from the beginning via the following steps: 1 -> 5 -> 9 -> end or 1 -> 5 -> 6 -> end. both of these combinations produce a series of 3 steps. 
and as you can see, you don't always have to take the maximum number of jumps at a specific position, you can take less jumps even though the number is higher.
if it is not possible to reach the end of the array, return -1.
