# SECOND LARGEST NUMBER

Initialize two variables largest and second_largest with the values of the first and second elements of the list, respectively.

Loop through the rest of the list, starting from the third element.

For each element in the list, compare it with the largest variable. If it is greater than largest, assign its value to second_largest and then assign the value of largest to element.

If the element is not greater than largest, compare it with second_largest. If it is greater than second_largest, assign its value to second_largest.

After looping through the entire list, second_largest will contain the second largest number in the list.

Return second_largest.
