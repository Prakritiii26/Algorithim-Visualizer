# Algorithm Visualizer

An interactive web application that visualizes common sorting algorithms through animated visualizations. This tool helps users understand how different sorting algorithms work by providing a step-by-step visual representation of the sorting process.

## 🚀 Features

- Real-time visualization of sorting algorithms
- Multiple sorting algorithm implementations:
  - Bubble Sort
  - Quick Sort
  - Merge Sort
- Interactive controls for better learning experience
- Adjustable animation speed
- Random array generation
- Color-coded visualization states
- Responsive design for all screen sizes

## 🛠️ Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- No external dependencies required

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/algorithm-visualizer.git
cd algorithm-visualizer
```

2. Open `index.html` in your web browser

That's it! No build process or dependencies required.

## 💻 Usage

1. **Generate New Array**: Click the "Generate New Array" button to create a new random array for sorting.

2. **Select Algorithm**: Choose your desired sorting algorithm from the dropdown menu:
   - Bubble Sort
   - Quick Sort
   - Merge Sort

3. **Adjust Speed**: Use the speed slider to control the animation speed:
   - Slide left for slower animation
   - Slide right for faster animation

4. **Start Sorting**: Click the "Sort!" button to begin the visualization

## 🎨 Visual Elements

- **Green Bars**: Unsorted elements
- **Orange Bars**: Elements being compared
- **Blue Bars**: Elements in their final sorted position

## 🔍 Algorithm Details

### Bubble Sort
- Time Complexity: O(n²)
- Space Complexity: O(1)
- Stable: Yes
- Implementation: Compares adjacent elements and swaps them if they are in the wrong order

### Quick Sort
- Time Complexity: O(n log n) average, O(n²) worst case
- Space Complexity: O(log n)
- Stable: No
- Implementation: Uses divide-and-conquer strategy with a pivot element

### Merge Sort
- Time Complexity: O(n log n)
- Space Complexity: O(n)
- Stable: Yes
- Implementation: Divides array into smaller subarrays, sorts, and merges them

