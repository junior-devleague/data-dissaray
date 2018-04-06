---
author:
- Somewha7
title: 'Data Disarray'
type: Activity
---

Summary
=======

Activity for learning about bubble sorts. Part of the Sorting Algorithm Series

Objective
=========

The nefarious Bubble Boy, sidekick to Dr. Monsoon, has sent a torrent of malicious code raining down on the file systems of Heroes Inc., where you work. Create a [bubble sort](https://en.wikipedia.org/wiki/Bubble_sort) to bring order back to all of the scrambled lists that he's left in his wake!

Prerequisites
=============

-   Basic usage of Python REPL


Requirements
============

-   Shell terminal or Python IDE
-   Some shuffled sets of numbers

Desired Outcomes
================

-   Basic understanding of sorting algorithms, and more specifically bubble sorts.

Tasks
=====

1.   Start by definining a function, with 1 argument -- a list to sort. This is your sort function, so call it something like sort(myList)
2.   Create a variable, called something like maxIteration, and make equal to the length of your input list -- this is the maximum amount of times that your sort function will iterate over your list.
3. Create a for loop that will run an amount of times equal to your maximum amount of iterations (for each loop)
4. Inside that for loop, create an index based for loop that will run an amount of times equal to the length of your list - 1
5. Inside that for loop, compare list[i] with list[i+1]. If list[i+1] < list[i], swap their positions. (*HINT*: you can define multiple variables on the same line with x, y = "1", "2". What if you define each of the index values of the list as being equal to the contents of the other one?)
6. Outside of your loops, return the function as being equal to your newly sorted input list.
7. Outside of your function, define a list as your input list. (make it out of order -- something like [3, 1, 7, 4, 2, 9, 1, 5, 3])
8. Print what your input list is.
9. Run your sort function on that list, saving it under a variable named something like output.
10. Print what your output list is.
### Choto Stretch Goals
-   create a list using user input rather than predefining it.
-   Currently the function is always running under it's worst case scenario -- if the list is so completely out of order that the first item should be the last item. add another detector to the function so that the function checks if the list before sorting is the same as the list after sorting. If that's the case, break out of the loop and return the list at that point rather than waiting for the function to go through the rest of the pointless loops.
