# OrderedList

A Java program that implements an ordered list using arrays and includes methods for searching, inserting, deleting, displaying, and merging ordered lists. The program demonstrates the functionality of these methods by inserting elements into two separate ordered lists and then merging them into a single ordered list. Here's a brief overview of the key parts of the code:

    OrderedList Class: This class represents the ordered list data structure. It contains private variables such as the array a to hold the elements, and numberOfElements to keep track of the current number of elements in the list.

    search Method: Performs binary search to find the index of an item in the ordered list. If found, it returns the index; otherwise, it returns -1.

    insert Method: Inserts an item into the ordered list using binary search to find the appropriate position. It shifts elements to accommodate the new item and increments numberOfElements.

    delete Method: Deletes an item from the ordered list if it exists. It searches for the item using the search method and shifts elements to fill the gap.

    display Method: Displays the elements of the ordered list.

    merge Method: Merges two ordered lists into a new ordered list by comparing elements from both lists and constructing a merged array.

    main Method: Demonstrates the usage of the ordered list methods. It creates two ordered lists a and b, inserts elements into them, merges them using the merge method, and displays the merged result.

Overall, the program effectively implements the ordered list data structure and demonstrates its functionality.
