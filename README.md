# Push_swap
 ``....a....``
 <div>
  
 ``....b....``
<img src="https://user-images.githubusercontent.com/18141491/213192271-8ef6cde7-4b00-4f05-aebc-24316cdfac62.png"  style="width:150px; height:150px;">  ``Simple andhighly effective algorithm project``



Write a program in C called push_swap which calculates and displays the smallest program that sorts the integers received as arguments.<br />

You have at your disposal a set of integer values, 2 stacks, and a limited set of instructions to manipulate both stacks. The goal is to sort the data in ascending order on a stack, using the lowest possible number of actions.<br />

*Sorting values is simple. To sort them the fastest way possible is less simple. Especially because from one integers configuration to another, the most efficient sorting solution can differ.*

## Rules

At the beginning:
* The stack a contains a random amount of negative and/or positive numbers which cannot be duplicated. The first argument should be at the top of the stack a
* The stack b is empty

The program must display the smallest list of instructions possible to sort the stack a, the smallest number being at the top. <br />

command  | action |
---|------|
`sa` | swap a - swap the first 2 elements at the top of *stack_a*					|
`sb` | swap b - swap the first 2 elements at the top of *stack_b*	|
`ss` | sa and sb at the same time |
`pa` | push a - take the first element at the top of b and put it at the top of a. Do nothing if b is empty|
`pb` | push b - take the first element at the top of a and put it at the top of b. Do nothing if a is empty |
`ra` | rotate a - shift up all elements of *stack_a* by 1. The first element becomes the last one			|
`rb` | rotate b - shift up all elements of *stack_b* by 1. The first element becomes the last one 		|
`rr` | ra and rb at the same time			|
`rra` |  reverse rotate a - shift down all elements of *stack_a* by 1. The last element becomes the first one	|
`rrb` |  reverse rotate b - shift down all elements of *stack_b* by 1. The last element becomes the first one	|
`rrr` | rra and rrb at the same time		|

## study_resources

* [how big_O notation works– explained with cake](https://www.freecodecamp.org/news/big-o-notation/) by [Cedd Burge](https://www.freecodecamp.org/news/author/cedd/)
* [the quicksort sorting algorithm video](https://www.youtube.com/watch?v=uXBnyYuwPe8) by [Back To Back SWE](https://www.youtube.com/channel/UCmJz2DV1a3yfgrR7GqRtUUA)
* [quick sort -ptbr](https://joaoarthurbm.github.io/eda/posts/quick-sort/) by João Arthur Brunet

## tools
* [push swap visualizer](https://github.com/o-reo/push_swap_visualizer) by [o-reo](https://github.com/o-reo)
* [push swap simulator](https://phemsi-a.itch.io/push-swap) by me
* [push_swap tester](https://github.com/laisarena/push_swap_tester) by [Lais Arena](https://github.com/laisarena)
* [push swap tester](https://github.com/LeoFu9487/push_swap_tester) by [LeoFu](https://github.com/LeoFu9487)
