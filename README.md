🚀 Passenger Counter App
A simple JavaScript-based application to count and track passengers.

📌 Features
✅ Increment passenger count with a button click.
✅ Save the current count and reset for a new entry.
✅ View previous saved counts.
✅ Simple and responsive UI.

🛠️ Technologies Used
HTML – Structure of the app

CSS – Styling for a clean UI

JavaScript – Functionality & DOM manipulation

🎯 How It Works
1️⃣ Click the "Increment" button to increase the count.
2️⃣ Click "Save" to record the current count and reset to 0.
3️⃣ Saved counts appear under "Previous Entries".

📂 Project Structure
bash
Copy
Edit
passenger-counter/
│── index.html # Main HTML file
│── style.css # Stylesheet for UI
│── script.js # JavaScript for functionality
└── README.md # Project documentation
🚀 Setup & Installation
Download or clone this repository:

sh
Copy
Edit
git clone https://github.com/your-username/passenger-counter.git
Open the index.html file in your browser.

📜 Code Overview
🔹 HTML
Defines the structure of the app.

html
Copy
Edit

<h2 id="count-display">0</h2>
<button id="increment-btn">Increment</button>
<button id="save-btn">Save</button>
<p>Previous Entries: <span id="save-el"></span></p>
🔹 CSS
Styles the UI for a clean look.

css
Copy
Edit
.container {
background: white;
padding: 20px;
text-align: center;
}
🔹 JavaScript
Handles user interactions using the DOM.

js
Copy
Edit
document.getElementById("increment-btn").addEventListener("click", function() {
count++;
countDisplay.textContent = count;
});
🎯 Future Improvements
✅ Add a Reset button.
✅ Store saved counts in localStorage.
✅ Add animations for a better user experience.

📝 License
This project is open-source under the MIT License.

💡 Contributions
Feel free to fork this project and enhance it! 🚀
