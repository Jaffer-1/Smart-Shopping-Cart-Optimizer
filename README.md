# Smart-Shopping-Cart-Optimizer
git clone https://github.com/Jaffer-1/Smart-Shopping-Cart-Optimizer.git
    ```
2.  **Open the project:**
    Simply open `index.html` in any modern web browser. No local server or installation is required as it uses Vanilla JavaScript.

---

## 👤 Author

**Jaffer Shaik**
*   GitHub: [@Jaffer-1](https://github.com/Jaffer-1)
*   Role: Developer & Algorithm Designer# Smart Shopping Cart Optimizer

The **Smart Shopping Cart Optimizer** is a lightweight, interactive web application designed to help users maximize the value of their grocery shopping within a specific budget. By utilizing a **Greedy Algorithm**, the app selects items that offer the highest "Utility Score" relative to their price.[cite: 3, 4]

---

## 🚀 Features

*   **Real-Time Optimization:** Input your budget and instantly see the best combination of items.[cite: 1, 4]
*   **Step-by-Step Visualization:** A detailed log explains why each item was either **PICKED** or **SKIPPED** based on the remaining budget.[cite: 1, 3]
*   **Value Ratio Analysis:** View items ranked by their efficiency (Utility/Price) to understand how the algorithm prioritizes selections.[cite: 1, 4]
*   **Responsive UI:** A clean, modern interface built with a mobile-first approach.[cite: 4, 5]
*   **Progress Tracking:** Visual progress bar showing what percentage of the budget has been utilized.[cite: 1, 4]

---

## 🛠️ Tech Stack

*   **HTML5:** Semantic structure for the dashboard and data tables.[cite: 4]
*   **CSS3:** Custom properties (variables), Flexbox, and Grid for a responsive, modern layout.[cite: 5]
*   **JavaScript (ES6+):** Vanilla JS using ES Modules for modular logic and DOM manipulation.[cite: 1, 3]

---

## 🧠 How the Algorithm Works

The application employs a **Greedy Algorithm** to solve a variation of the Knapsack Problem.

1.  **Ratio Calculation:** For every item, the algorithm calculates a "Value Ratio":
    $$\text{Ratio} = \frac{\text{Utility Score}}{\text{Price}}$$
2.  **Sorting:** Items are sorted in descending order based on this ratio.[cite: 1, 3]
3.  **Selection:** The algorithm iterates through the sorted list, picking every item it can afford until the budget is exhausted.[cite: 3]

### Efficiency
The algorithm is highly efficient with a time complexity of:
$$O(N \log N)$$
This is primarily due to the sorting step, where $N$ is the number of items available.[cite: 4]

---

## 📂 Project Structure

*   `index.html` – The main entry point and UI structure.[cite: 4]
*   `style.css` – Contains all styling and responsive design rules.[cite: 5]
*   `app.js` – Handles DOM events, rendering, and application state.[cite: 1]
*   `greedy.js` – Contains the core logic for the greedy optimization.[cite: 3]
*   `data.js` – The dataset containing grocery items, categories, prices, and utility scores.[cite: 2]

---

## 💻 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Jaffer-1/Smart-Shopping-Cart-Optimizer.git
    ```
2.  **Open the project:**
    Simply open `index.html` in any modern web browser. No local server or installation is required as it uses Vanilla JavaScript.

---

## 👤 Author

**Jaffer Shaik**
*   GitHub: [@Jaffer-1](https://github.com/Jaffer-1)
*   Role: Developer & Algorithm Designer[cite: 1, 4]
