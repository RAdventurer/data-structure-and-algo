# data-structure-and-algo
It seems you're asking for a description of the code provided. Let's break it down:

1. **Bubble Sort Function (`bubble_sort`):**
   - This function implements the Bubble Sort algorithm to sort a list of numbers in ascending order.
   - The function iterates over the list multiple times, comparing adjacent elements and swapping them if they are in the wrong order.
   - This process is repeated until the list is sorted.

2. **Insertion Sort Function (`insertion_sort`):**
   - This function implements the Insertion Sort algorithm to sort a list of numbers in ascending order.
   - It iterates over the list, considering one element at a time and inserting it into its correct position among the already sorted elements.
   - This process is repeated until all elements are in the correct order.

3. **Merge Sort Functions (`merge_sort` and `merge`):**
   - `merge_sort` is a recursive function that implements the Merge Sort algorithm to sort a list of numbers in ascending order.
   - It divides the list into two halves, sorts each half recursively, and then merges the sorted halves.
   - `merge` is a helper function used by `merge_sort` to merge two sorted lists into a single sorted list.

4. **Custom Comparison Functions:**
   - There are custom comparison functions defined to compare objects based on different attributes. For example, `compare_likes` compares notebooks based on their `likes` attribute.
   - These comparison functions are used as arguments to the `merge_sort` function to enable sorting objects based on different attributes.

5. **Testing:**
   - The code includes several test cases for each sorting algorithm to ensure they work correctly.
   - These test cases cover various scenarios such as sorting lists with different lengths, lists containing repeating elements, empty lists, etc.
   - The `evaluate_test_cases` function is used to automatically run these test cases and validate the sorting algorithms.
