# ⚡ SORTIFY — Interactive Sorting Algorithm Visualizer

> **See how algorithms think. Watch how data moves. Master sorting visually.**
>
> Explore, compare, and understand 12 different sorting algorithms through real-time animated visualizations. A browser-based educational tool built using HTML, CSS, and JavaScript — all inside one standalone HTML file.

---

## ✨ Features

### 🔢 12 Sorting Algorithms

Explore and visualize these sorting algorithms:

- 🫧 **Bubble Sort** — Repeatedly compares and swaps adjacent elements.
- 🎯 **Selection Sort** — Finds the minimum or maximum element and places it in position.
- 📥 **Insertion Sort** — Builds a sorted section by inserting elements into their correct positions.
- 🔀 **Merge Sort** — Divides the array and merges sorted sections.
- ⚡ **Quick Sort** — Uses a pivot to partition elements into smaller sections.
- 🏗️ **Heap Sort** — Uses a binary heap to organize and sort elements.
- 🐚 **Shell Sort** — Improves insertion sort using decreasing gaps.
- 🔢 **Counting Sort** — Sorts elements by counting their occurrences.
- 🔟 **Radix Sort** — Sorts numbers digit by digit.
- 🪣 **Bucket Sort** — Distributes elements into buckets and sorts them.
- 🔄 **Cocktail Shaker Sort** — Moves through the array in both directions.
- 🪮 **Comb Sort** — Improves bubble sort using a shrinking gap.

### 🎮 Interactive Visualization

- Watch sorting algorithms execute through animated bars.
- Identify comparisons, swaps, and element movements.
- Highlight elements currently being compared.
- Observe sorted elements as the algorithm progresses.
- Understand how each algorithm changes the array.

### ⏯️ Playback Controls

- ▶️ Play the sorting animation.
- ⏸️ Pause the visualization.
- ⏭️ Move forward one step.
- ⏮️ Move backward through available steps.
- 🔄 Reset the current visualization.
- ⚡ Adjust animation speed.

### 📊 Algorithm Analysis

- Display time complexity.
- Display space complexity.
- Show best-case, average-case, and worst-case performance.
- Track comparisons, swaps, and writes.
- Display the number of operations during execution.
- Explore algorithm pseudocode.

### 🎨 Modern User Interface

- Premium dark interface with purple and cyan accents.
- Glass-inspired panels and gradient effects.
- Animated sorting bars.
- Interactive algorithm selection menu.
- Dedicated algorithm information panel.
- Responsive layout for desktop and mobile devices.
- Smooth transitions and modern visual effects.

### ⚙️ Customization

- Generate random arrays.
- Change the array size.
- Enter custom array values.
- Select ascending or descending order.
- Adjust sorting speed.
- Switch between different algorithms.

---

## 📂 Project Structure

```text
SORTIFY_Sorting_Visualizer/
│
├── SORTIFY_Sorting_Visualizer.html  ← Complete web application
├── README.md                       ← Project documentation
└── LICENSE                         ← Project license
```

The entire application is contained in a single HTML file, including:

- HTML structure
- CSS styling
- JavaScript algorithms
- Animation and visualization logic
- Interactive playback controls
- Algorithm information and complexity analysis

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/rsamwilson2323-cloud/SORTIFY_Sorting_Visualizer.git
```

### 2️⃣ Open the Project Folder

```bash
cd SORTIFY_Sorting_Visualizer
```

### 3️⃣ Run the Application

Open `SORTIFY_Sorting_Visualizer.html` in any modern web browser.

**Windows users:** Double-click the HTML file to launch the application in your default browser.

✅ No installation process required.

---

## 📦 Requirements

```text
HTML5             Application structure
CSS3              Styling and animations
JavaScript        Sorting algorithms and application logic
Modern Web Browser Chrome, Edge, Firefox, etc.
```

**No additional dependencies are required.**

- No Python
- No Node.js
- No npm packages
- No database
- No backend server

---

## 🚀 Live Demo

You can publish SORTIFY using GitHub Pages.

**Repository:**  
https://github.com/rsamwilson2323-cloud/SORTIFY_Sorting_Visualizer

**Application file:**  
https://github.com/rsamwilson2323-cloud/SORTIFY_Sorting_Visualizer/blob/main/SORTIFY_Sorting_Visualizer.html

To publish the application:

1. Open the repository's **Settings → Pages**.
2. Select the `main` branch.
3. Choose `/ (root)` as the publishing folder.
4. Click **Save**.

GitHub Pages will generate a website URL after publishing completes.

---

## ▶️ Usage

### 🔢 1. Select a Sorting Algorithm

1. Open the application.
2. Explore the sorting algorithm menu.
3. Select an algorithm such as Bubble Sort, Merge Sort, or Quick Sort.
4. View its algorithm description and complexity information.

### 🎲 2. Generate an Array

1. Choose the array size.
2. Generate a random array.
3. Alternatively, enter your own array values.
4. Select ascending or descending order.

### ▶️ 3. Start Visualization

1. Select an algorithm.
2. Click **Play** to start the animation.
3. Watch the bars move into their correct positions.
4. Observe comparisons, swaps, and writes.
5. Adjust the speed whenever required.

### ⏯️ 4. Control the Animation

- Click **Pause** to stop the animation.
- Click **Step Forward** to observe the next operation.
- Click **Step Backward** to revisit an earlier operation.
- Click **Reset** to restart the visualization.
- Change the speed to observe operations more clearly.

### 📊 5. Understand Algorithm Performance

Explore:

- Best-case time complexity.
- Average-case time complexity.
- Worst-case time complexity.
- Space complexity.
- Number of comparisons.
- Number of swaps and writes.
- Algorithm pseudocode.

---

## 🧠 Sorting Algorithm Complexity

| Algorithm | Best Case | Average Case | Worst Case |
|---|---:|---:|---:|
| Bubble Sort | O(n) | O(n²) | O(n²) |
| Selection Sort | O(n²) | O(n²) | O(n²) |
| Insertion Sort | O(n) | O(n²) | O(n²) |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) |
| Quick Sort | O(n log n) | O(n log n) | O(n²) |
| Heap Sort | O(n log n) | O(n log n) | O(n log n) |
| Shell Sort | Depends on gap sequence | Depends on gap sequence | Depends on gap sequence |
| Counting Sort | O(n + k) | O(n + k) | O(n + k) |
| Radix Sort | O(d(n + k)) | O(d(n + k)) | O(d(n + k)) |
| Bucket Sort | O(n + k) | Depends on distribution | O(n²) |
| Cocktail Shaker Sort | O(n) | O(n²) | O(n²) |
| Comb Sort | O(n log n) typical | O(n²) | O(n²) |

*Note: `n` represents the number of elements, `k` represents a value range or bucket-related parameter, and `d` represents the number of digits. Shell Sort complexity depends on its gap sequence.*

---

## 🛠️ Key Technical Details

| Feature | Implementation |
|---|---|
| Frontend | HTML5 |
| Styling | CSS3 |
| Application logic | Vanilla JavaScript |
| Sorting algorithms | JavaScript |
| Visualization | Animated HTML elements |
| Playback | JavaScript animation controls |
| Performance tracking | Operation counters |
| Algorithm information | Complexity and pseudocode |
| Data input | Random and custom arrays |
| Backend | Not required |
| Database | Not required |

---

## 📌 Important Notes

- SORTIFY is designed for educational purposes.
- Sorting animations demonstrate the internal operations of algorithms.
- Performance measurements shown in the application are operation counters, not hardware benchmarking results.
- Actual execution time depends on array size, browser, and device performance.
- Some algorithms require specific input constraints, such as non-negative integer values for Counting Sort and Radix Sort.
- Algorithm complexity can vary based on implementation and input distribution.
- The application runs locally in the browser.

---

## 🚀 Future Improvements

- 📈 Add side-by-side algorithm comparisons.
- 🏆 Add a sorting speed competition mode.
- 📊 Add real-time performance graphs.
- 🧩 Add more sorting algorithms.
- 🎓 Add interactive sorting challenges.
- 🧠 Add algorithm quizzes and practice tests.
- 🎨 Add light and dark themes.
- 📱 Improve mobile visualization controls.
- 📥 Export sorting statistics.
- 🎬 Add visualization recording and replay.
- 🔍 Add detailed explanations for every sorting operation.

---

## ⚠️ Disclaimer

This project is intended for educational and personal use. It demonstrates how different sorting algorithms work through interactive visualizations.

**SORTIFY is an algorithm learning and visualization tool, not a professional benchmarking platform.**

---

## 👨‍💻 Author

**Sam Wilson**

🌐 GitHub: https://github.com/rsamwilson2323-cloud

💼 LinkedIn: https://www.linkedin.com/in/sam-wilson-14b554385/

---

## 📜 License

This project is distributed under the license provided in the repository's `LICENSE` file.

---

<div align="center">

### ⚡ SORTIFY

**Don't just learn algorithms. Watch them work.**

*Built with HTML, CSS, and JavaScript.*

</div>
