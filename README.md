# Pyodide
Browser-based Python quiz for EDA and data visualization. Runs Pandas, NumPy and Matplotlib in the browser with Pyodide, no server needed. Includes auto-checking, anti-cheating controls and downloadable results.
# Python EDA Quiz Lab

A single-file, browser-based Python quiz for teaching Exploratory Data Analysis (EDA) and data visualization. Students write Pandas and Matplotlib code and get instant feedback. Python runs entirely in the browser using [Pyodide](https://pyodide.org), so no server or installation is needed.

## Features
- 10 auto-checked questions: data cleaning, groupby, correlation, and 4 graph tasks
- Built-in code editor with Run and Check Answer buttons
- Student name and roll number on start
- Anti-cheating controls: copy/paste, right-click, DevTools shortcuts and tab switching are blocked or counted; the quiz auto-submits after 4 violations
- Downloadable result report (.txt) with score and violation log
- Python runs in a Web Worker, so the page stays responsive

## How to use
1. Open the live link: `https://YOUR-USERNAME.github.io/REPO-NAME/`
2. Wait for "Ready" (first load takes 10-20 seconds)
3. Enter your name and roll number, then click **Start Quiz**
4. When done, click **Finish & Submit** and download your result

**Requirements:** Chrome (recommended) and an internet connection.

## Customize
Questions live in the `Q` array inside `index.html`. Each question has a title, a description, starter code and a Python check expression.

## Limitations
This is a browser-only tool. It discourages cheating but cannot fully prevent it, so it is best used with a teacher supervising.

## Author
Muhammad Zarq Ali (Engeenior)
