![push_swapn](https://user-images.githubusercontent.com/18141491/213209505-c9c4c4cb-8fc6-46c1-b288-54b15f21fc3e.png)
# 42-push-swap

Write a program in C called push_swap which calculates and displays the smallest program that sorts the integers received as arguments.<br />

You have at your disposal a set of integer values, 2 stacks, and a limited set of instructions to manipulate both stacks. The goal is to sort the data in ascending order on a stack, using the lowest possible number of actions.<br />

*Sorting values is simple. To sort them the fastest way possible is less simple. Especially because from one integers configuration to another, the most efficient sorting solution can differ.*

## Rules

At the beginning:
* The stack a contains a random amount of negative and/or positive numbers which cannot be duplicated. The first argument should be at the top of the stack a
* The stack b is empty

The program must display the smallest list of instructions possible to sort the stack a, the smallest number being at the top. <br />

The following operations are allowed:
* sa (swap a): Swap the first 2 elements at the top of stack a. Do nothing if there is only one or no elements.
* sb (swap b): Swap the first 2 elements at the top of stack b. Do nothing if there is only one or no elements.
* ss : sa and sb at the same time.
* pa (push a): Take the first element at the top of b and put it at the top of a. Do nothing if b is empty.
* pb (push b): Take the first element at the top of a and put it at the top of b. Do nothing if a is empty.
* ra (rotate a): Shift up all elements of stack a by 1. The first element becomes the last one.
* rb (rotate b): Shift up all elements of stack b by 1. The first element becomes the last one.
* rr : ra and rb at the same time.
* rra (reverse rotate a): Shift down all elements of stack a by 1. The last element becomes the first one.
* rrb (reverse rotate b): Shift down all elements of stack b by 1. The last element becomes the first one.
* rrr : rra and rrb at the same time.

To better understand these operations you can play this [game](https://phemsi-a.itch.io/push-swap) made by [Paula Hemsi](https://github.com/paulahemsi)
