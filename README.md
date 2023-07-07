# Sorting Algorithms Visualised

This project is an educational visualiser website which allows the user to see how a variety of sorting algorithms operate, and compare their efficiency for different kinds of inputs. 

Sorting algorithms operate on an initially unsorted list of positive integers, where each element is represented visually as a vertical bar, with a height proportional to the integer's size. Lists are randomly generated to be sorted; the user can adjust the length of the list from 1 to 1000, as well as the maximum integer value of each element also from 1 to 1000.

To sort the list, users can select between quadratic algorithms such as selection sort, insertion sort, bubble sort and cocktail shaker sort, as well as faster logarithmic algorithms such as merge sort, quick sort and heap sort. By clicking the 'Sort' button, the algorithm is ran one operation at a time at a speed adjustable with the speed slider.

Bars are coloured yellow to represent comparisons, red to represent swaps, and pink to represent other miscellaneous properties unique to the algorithm such as the minimum value in selection sort or the pivot value in quick sort. A running total is kept for the total number of comparisons performed during the operation of the sort, which allows the efficiency of algorithms to be compared.
