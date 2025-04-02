# 😴 Sleep Debt Tracker

A simple, modern, single-page web application designed to help you track your sleep hours over a 7-day period and calculate your weekly sleep debt or surplus. Built entirely with plain HTML, CSS, and JavaScript, focusing on ease of use and a clean interface.

![image](https://github.com/user-attachments/assets/3d59d3ef-32b5-4890-8192-aeabf6734a15)

---

## ✨ Features

*   **🛏️ Daily Sleep Input:**
    *   Log hours slept for each day (Monday - Sunday) using intuitive range sliders (0–12 hours).
    *   Selected sleep duration clearly displayed next to each slider.
    *   Set your personal ideal sleep duration per night (defaults to 8 hours).
*   **📊 Automatic Calculations:**
    *   Calculates and displays your total actual sleep for the tracked week.
    *   Calculates your total ideal sleep based on your goal.
    *   Clearly shows the difference: your sleep debt (negative, shown in red) or surplus (positive, shown in green).
    *   Example summary: “📉 You're -6.0 hours behind this week.” or “🎉 You're +3.0 hours ahead!”.
*   **📈 Visual Feedback:**
    *   A simple bar chart visualizes your sleep hours for each day of the week.
    *   Displays a dynamic motivational message based on your overall sleep status (e.g., “Doing great! 💪” or “You might need some rest 😴”).
*   **💾 Persistent Storage:**
    *   Uses browser `localStorage` to save your daily sleep entries, ideal sleep goal, selected theme, and daily moods.
    *   Your data persists even after refreshing the page or closing and reopening the browser.
*   **🌗 Modern Design:**
    *   Clean, responsive, and mobile-friendly layout.
    *   Includes a **Light/Dark mode** toggle for user preference.
    *   Readable fonts, appropriate padding, and rounded elements for a modern aesthetic.
*   **🧠 Optional Extras:**
    *   Displays a randomly chosen **Sleep Hygiene Tip** on each load.
    *   Includes an optional **daily mood selector** (😊 😐 😴 😠 🤔) which is also saved locally.
*   **🔒 Client-Side Focus:**
    *   All calculations and storage happen directly in your browser. No data is sent to any server.

---

## 🚀 Getting Started

Using the Sleep Debt Tracker is incredibly simple:

1.  **Download:** Obtain the `index.html` file.
2.  **Open:** Open the `index.html` file directly in your preferred modern web browser (like Chrome, Firefox, Safari, Edge).

That's it! The application will load, and you can start tracking your sleep.

---

## 🛠️ How to Use

1.  **Set Your Goal:** Adjust the "Your Ideal Sleep Goal" input to your desired nightly sleep duration.
2.  **Log Daily Sleep:** Use the sliders for each day of the week to input the hours you slept. The number next to the slider updates automatically.
3.  **Select Mood (Optional):** Choose an emoji from the dropdown next to each day's slider to represent your mood for that day.
4.  **View Results:** The "Weekly Summary" section updates automatically, showing your total sleep, ideal sleep, and the calculated debt or surplus.
5.  **See the Chart:** The bar chart visually represents the sleep data you entered. Hover over bars to see the exact hours.
6.  **Toggle Theme:** Use the 🌓 button in the top-right corner to switch between light and dark modes.
7.  **Get a Tip:** Read the randomly selected sleep hygiene tip at the bottom.

Your entered data (sleep hours, goal, moods, theme) will be automatically saved in your browser's `localStorage` and loaded the next time you open the app.

---

## 💻 Technology Stack

*   **HTML5:** Semantic structure for the web page.
*   **CSS3:** Custom styling, responsiveness, variables for theming (Light/Dark mode).
*   **JavaScript (ES6+):** Core application logic, DOM manipulation, calculations, `localStorage` interactions, event handling.
*   **No Frameworks/Libraries:** Built purely with vanilla web technologies.

---

## 💾 Persistence Details

*   The application uses the browser's `localStorage` API to store data.
*   Keys used:
    *   `sleepTrackerData_v1`: Stores an object containing `idealSleep`, `dailySleep` (hours per day), and `dailyMoods`.
    *   `sleepTrackerTheme`: Stores the user's selected theme ('light' or 'dark').
*   **Note:** `localStorage` is specific to the browser and domain (or local file path). Data is stored unencrypted and is suitable for non-sensitive preferences like this, but not for secure information. Clearing browser data will remove saved sleep entries.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! If you have suggestions for improvement, feel free to open an issue or submit a pull request (if this were hosted on a platform like GitHub).

---

## 📜 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT). (Assuming MIT - adjust if different)
