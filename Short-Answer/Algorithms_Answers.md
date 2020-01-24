#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n). Each increase in n increases the runtime by n. If n = 1, the while loop runs 1 time. If n = 2, the while loop runs 2 times, etc.


b) O(logn). As n increases, the runtime does not increase every time. Runtime grows at a slower rate than n.


c) O(n). Runtime increases at the same rate as n.

## Exercise II

Starting from the first floor, I would throw an egg from each floor until I broken an egg. Then I would go down a floor and stay there until I was no longer worried about my eggs.

As I continue to think about the issue, I recall that binary search may result in lower time complexity. But knowing what I know about eggs, and assuming they are raw, I would stick with my floor by floor method. Also, the taller the building is, the more sense it would make go floor by floor.

Floor by floor is  O(n).
Binary search is O(log n).
