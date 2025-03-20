# Sorting Visualizer

Sorting Visualizer is an interactive web application that visualizes various sorting algorithms. This tool is perfect for educational purposes, helping students and developers understand how different sorting algorithms work by visualizing them in real-time.

## Features

- Visualizes different sorting algorithms including Bubble Sort, Selection Sort, Merge Sort, and Quick Sort.
- Adjustable data size and sorting speed.
- Displays the time taken by the algorithm to complete the sorting.
- Interactive UI with a simple reset functionality.

## Algorithms Implemented

1. **Bubble Sort**: A simple comparison-based algorithm where each pair of adjacent elements is compared, and the elements are swapped if they are in the wrong order. This process is repeated until the array is sorted.

2. **Selection Sort**: This algorithm divides the input list into two parts: the sorted part at the left end and the unsorted part at the right end. Initially, the sorted part is empty, and the unsorted part is the entire list. The smallest (or largest, depending on sorting order) element is selected from the unsorted part and swapped with the leftmost element, and that element becomes a part of the sorted part.

3. **Merge Sort**: A divide and conquer algorithm that divides the array into two halves, recursively sorts them, and finally merges the two sorted halves to produce the sorted array.

4. **Quick Sort**: Another divide and conquer algorithm that selects a 'pivot' element from the array and partitions the other elements into two sub-arrays, according to whether they are less than or greater than the pivot. The sub-arrays are then sorted recursively.

## Getting Started

### Prerequisites

To run the Sorting Visualizer locally, you'll need a basic web server to serve the files, or you can open the `index.html` file directly in your browser.

### Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/YourUsername/Sorting_Visualizer.git
    cd Sorting_Visualizer
    ```

2. Open `index.html` in your web browser:

    ```bash
    open index.html
    ```

### Usage

- **Algorithm Selection**: Choose an algorithm from the "Algorithms" dropdown menu to visualize it.
- **Data Size Slider**: Adjust the slider to increase or decrease the size of the data set to be sorted.
- **Speed Slider**: Adjust the speed at which the algorithm runs.
- **Reset**: Reset the visualizer to start over with a new random data set.
- **Time Display**: See the time taken by the algorithm to sort the data set.

### Folder Structure

- **index.html**: The main HTML file that renders the UI.
- **style.css**: Contains all the CSS styles for the application.
- **sketch.js**: Contains the core logic for setting up and drawing the visualization.
- **algorithms.js**: Contains the generator functions for the sorting algorithms.
- **timer_algos.js**: Contains the functions to measure the time taken by the sorting algorithms.
- **libraries**: Contains additional libraries used by the application.
- **images**: Contains images used in the README and other parts of the repository.
- **gif.gif**: Demonstrates the visualization in action.


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

1. Fork the project.
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a pull request.


