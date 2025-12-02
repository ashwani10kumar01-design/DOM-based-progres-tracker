# Ascension 🏋️‍♂️

**Ascension** is a minimalist, dark-themed personal gym progress tracker designed to help you stay consistent with your fitness goals. It allows users to log daily weight and body fat percentages, view historical data, and track overall progress metrics without the need for complex accounts or backend databases.

## 📸 Features

* **Dashboard Analytics:** Instantly view your latest weight, total weight change (calculated automatically), and total number of logs.
* **CRUD Functionality:** full capability to **C**reate, **R**ead, **U**pdate, and **D**elete log entries.
* **Data Persistence:** Uses `localStorage` to save your data directly in your browser. No data leaves your device.
* **Simple Authentication:** A lightweight client-side "Access Key" system to keep your logs private on shared devices.
* **Motivational UI:** Features a sleek "Dark Mode" aesthetic with neon green accents and rotating motivational quotes.
* **Responsive Design:** Fully optimized for mobile and desktop usage.

## 🛠 Tech Stack

* **HTML5**
* **CSS3** (Flexbox, Grid, Custom Variables)
* **Vanilla JavaScript** (DOM Manipulation, LocalStorage API)
* **FontAwesome** (Icons)
* **Google Fonts** (Montserrat)

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/ascension-tracker.git](https://github.com/yourusername/ascension-tracker.git)
    ```
2.  **Open the application:**
    Simply navigate to the folder and open `index.html` in your web browser. No build step or server is required.

## 🔑 Access Key

By default, the application is locked.
* **Default Key:** `1234`

*You can change this key by modifying the `LOGIN_KEY` constant in `script.js`.*

## 📂 Project Structure

```text
/
├── index.html      # Main HTML structure
├── style.css       # Styling, themes, and responsive media queries
└── script.js       # Logic for state management, UI rendering, and storage
