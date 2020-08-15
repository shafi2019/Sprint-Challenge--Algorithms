#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) = The runtime complexity depends on the values of n


b) O(n^2) = the rutime complexity  is exponential due to the nested loop ( loop inside a loop). n* * n* = n^2


c) O(n) = The runtime compleixity will depend on the value of n

## Exercise II
We can use recursive binarry search to determine (f) which is used to minimize number of borken/dropped egges.
def minimize_eggs(n):
    list of floors = [0,1...n]
take the middle point in building: if the egg is broken taken the middle down otherwise take the middle up part of the building.
Loop until there is only 1 egg left
The runtime is Logarithmic Time -  O(log n)

To mitigate only for breaking eggs, use a linear search. The array would be sorted from lowest floor to highest. Loop through, moving higher and higher. Only one egg would break when it does, that would be the f floor.
