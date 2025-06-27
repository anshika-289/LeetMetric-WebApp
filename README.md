# 💡 LeetMetric

LeetMetric is a lightweight web application that allows users to fetch and visualize their LeetCode statistics by entering their LeetCode username. It displays solved problems by difficulty level and shows submission statistics using interactive progress circles and stat cards.

---

## 🧩 Features

- 🔍 Search for any LeetCode username
- 🟢 Easy, 🟡 Medium, 🔴 Hard problem progress visualization via animated circular charts
- 📊 Submission stats shown in summary cards
- 🧪 Basic validation for username input
- 🌐 Uses LeetCode GraphQL API (with CORS proxy)

---

## 📁 Project Structure

LeetMetric/
│
├── index.html # Main HTML structure
├── style.css # App styling
├── script.js # Main JS logic for fetching and rendering data

---

## 🚀 How to Use

1. Clone or download this repository.

2. Open `index.html` in your browser.

3. Enter your **LeetCode username** in the input box and click **Search**.

4. View your progress and submission stats instantly!

---

## ⚙️ Technologies Used

- **HTML5** – Structuring the layout
- **CSS3** – Styling and layout design
- **JavaScript (ES6)** – Dynamic content rendering and API interaction
- **LeetCode GraphQL API** – Fetching user statistics
- **CORS Anywhere Proxy** – Bypassing CORS limitations

---

## 🔒 Disclaimer

This project uses a third-party proxy (`https://cors-anywhere.herokuapp.com/`) to bypass CORS restrictions. For production deployment, consider using a secure proxy server or deploy server-side middleware.

---

