Add your answers to the Algorithms exercises here.

#1.
    a) -> O(n)
    b) -> O(n^3) 
    c) -> O(n)

#2.
Start at the middle of the building:
middle = f/2
If the egg breaks then we know we have to test the other half of the floors. Just keep dividing floors until the egg do not break. When the egg do not break we test floor by floor.

So something like that:
if egg did not break we test on the floor:
(lastFloor + lastFloor/2)
But if the egg breaks, then we test on the floor:
(lastFloor - lastFloor/2).

That does look to me like a quicksort could be a tool for the problem to sort. And i guess we would look at O(n log n) complexity in this case.
