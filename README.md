# Smart Shopping Cart Optimizer 🛒

A sleek, vanilla JavaScript application that uses a **Greedy Algorithm** to help users maximize the "utility" or value of their grocery shopping within a specific budget.

## 🚀 Features
* **Greedy Optimization:** Automatically selects items based on the highest Value-to-Price ratio.
* **Real-Time Breakdown:** Displays a step-by-step log of why the algorithm picked or skipped an item.
* **Visual Progress:** Tracks budget usage with a dynamic progress bar.
* **Responsive Design:** Clean UI built with CSS3 and Poppins typography.

## 🧠 How the Algorithm Works
The core logic follows a classic **Greedy Approach**:
1. **Ratio Calculation:** Each item is assigned a value ratio: $Ratio = \frac{Utility}{Price}$.
2. **Sorting:** Items are sorted in descending order based on this ratio.
3. **Selection:** The algorithm iterates through the sorted list, picking every item it can afford until the budget is exhausted.

**Time Complexity:** $O(n \log n)$ due to the sorting requirement.

## 🛠️ Tech Stack
* **HTML5:** Semantic structure.
* **CSS3:** Custom properties (variables) and Flexbox/Grid layouts.
* **JavaScript (ES6):** Modular structure using `import/export`.

## 📂 File Structure
* `index.html` - The main entry point and UI structure.
* `style.css` - Custom styling and responsive layouts.
* `app.js` - DOM manipulation and event handling.
* `greedy.js` - The core optimization logic.
* `data.js` - The grocery item dataset.

## ⚙️ How to Run
1. Clone the repository.
2. Open `index.html` in any modern web browser.
3. *Note: Because this project uses ES6 Modules, you may need to run it through a local server (like VS Code's "Live Server" extension) to avoid CORS issues.*

---
Built with ❤️ in 2026.
