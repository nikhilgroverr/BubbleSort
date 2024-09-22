# BubbleSort
There are two java code for bubbleSort (1. simpleBubbleSortVisulizer, 2. AdvanceBubbleSortVisualizer)


1. Class Structure
Previous Code: Implemented a selection sort visualizer with a simple GUI that painted bars representing the array elements.
Current Code: Implements a bubble sort visualizer with a more extensive GUI that includes buttons for various user actions and a dynamic display of sorting statistics.

2. Sorting Algorithm
Previous Code: Uses the selection sort algorithm. The sorting process is straightforward, but the visualization is less interactive.
Current Code: Uses the bubble sort algorithm, which is typically easier for beginners to understand and visualize due to its iterative nature.

3. User Interface
Previous Code: Simple JFrame and JPanel setup with limited interactivity. Only draws the sorting process without controls.
Current Code: Features a comprehensive control panel that allows users to:
Enter the array size
Generate and randomize the array
Start sorting with adjustable speed
Reset the array
View real-time statistics (comparisons and swaps)

4. Visualization Details
Previous Code: Color-coded bars for the array elements during sorting, but without real-time feedback on comparisons or swaps.
Current Code: Enhanced visualization with different colors for:
Sorted elements (green)
Currently comparing elements (blue)
Unsorted elements (red)
It also includes a legend explaining the colors.

5. Performance Statistics
Previous Code: Did not track or display performance statistics during sorting.
Current Code: Tracks and displays the number of comparisons and swaps made during the sorting process, providing valuable insights into the algorithm’s behavior.

6. Responsiveness and Usability
Previous Code: The sorting process is blocking, meaning that users cannot interact with the GUI while sorting is happening.
Current Code: Uses a separate thread for sorting, allowing the UI to remain responsive. Users can adjust the speed of the sorting animation dynamically.

7. Code Maintainability
Previous Code: Simpler and more straightforward but less modular.
Current Code: More structured with methods handling specific tasks (e.g., generateArray, disableButtons, createColorBox), making it easier to read and maintain.
