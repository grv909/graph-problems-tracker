# 🧠 Graph Problem Tracker

A simple, interactive web application to help you track your progress on a curated list of graph theory problems. This tool is designed for students and developers preparing for technical interviews or looking to strengthen their understanding of graph algorithms.

---

## ✨ Features

* **Pre-loaded Problem List:** Comes with a comprehensive list of graph problems sorted by common patterns (e.g., Traversal, Topological Sort, Shortest Path).
* **Interactive Checkboxes:** Easily mark problems as "Done" to track your progress.
* **Spaced Repetition Reminders:** When you solve a problem, a 10-day review timer starts. The status will change to "Review ⚠️" after 10 days to remind you to revisit the concept.
* **Solve Count:** Tracks how many times you've completed each problem, encouraging repeated practice.
* **Progress Visualization:** An overall progress bar and per-category counters give you a clear view of your completion status.
* **Persistent Storage:** Your progress is automatically saved in your browser's local storage, so you can pick up where you left off.
* **Direct Links:** Each problem links directly to its page on LeetCode or GeeksforGeeks for convenience.
* **Responsive Design:** The interface is designed to work smoothly on both desktop and mobile devices.

---

## 🚀 How to Use

1.  **Browse the categories:** The problems are organized into collapsible accordion sections based on graph patterns.
2.  **Mark your progress:** Click the checkbox in the "Done" column to mark a problem as completed. This will:
    * Start the 10-day review timer.
    * Increment the "Count" for that problem.
    * Update the progress bars.
3.  **Revisit problems:** To reset the review timer and increase the solve count, simply uncheck and re-check the problem.
4.  **No need to save manually!** All changes are saved to your browser automatically.

---

## 💻 Tech Stack

* **HTML5:** For the basic structure of the web page.
* **Tailwind CSS:** For modern and responsive styling.
* **JavaScript (ES6):** For all the application logic, including progress tracking, DOM manipulation, and handling user interactions.
