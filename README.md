# sorting-Algorithm
Sorting is done to make it easier to search through a given
data sample efficiently and quickly.
Here the first thing  we have to do is comparing of the elements
with fist element to the next.lets say 7 and 4 are the elements
now we have to swap with 4 as 7 is greater than 4. And again compare 
the 2nd element with the 3rd say, 7 and 8 since 7 is less than 8 so we 
we will not gonna swap it and this process will continue for the 4th (next)
elements as well.To pass the elements we have to completely check the arrays.
we push the greater element of arrays of ecah pass.
 e.g:- (7 4 8 1 9)->( 4 7 8 1 9) swaps since 7>4
(4 7 8 1 9)->(4 7 8 1 9) no swaps since 7<8 
(4 7 8 1 9)->(4 7 1 8 9) swaps since 8>1
(4 7 1 8 9)->(4 1 7 8 9) swaps since 7>1
(4 1 7 8 9)->(1 4 7 8 9) swaps since 4>1 
(1 4 7 8 9)->(1 4 7 8 9) hence, this is the sorted arrays.
