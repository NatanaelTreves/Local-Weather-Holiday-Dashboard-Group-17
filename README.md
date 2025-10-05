**Local Weather & Holiday Dashboard
📌 Project Overview**





This project is part of WAD621S – Web Application Development at the Namibia University of Science and Technology **(NUST)**.





**Our application, Local Weather & Holiday Dashboard, provides:**

⏰ Live Local Time & Date

🌦️ Real-time Weather Updates (via OpenWeather API / mock fallback)

📅 Upcoming Holidays List (loaded from holidays.json)

📆 Weekend Countdown Timer


The dashboard combines HTML, CSS, JavaScript, and JSON to deliver an interactive and visually appealing interface.





**👨‍💻 Team Members**

Natanael N Treves (Group Leader) – 224032143

Rejoice Kaulumah – 224061135





**🛠️ Technologies Used**

HTML5 – Structure & layout

CSS3 – Styling & responsive design

JavaScript (ES6) – Logic, API calls, dynamic updates

JSON – Holiday data

OpenWeather API – For live weather (optional API key integration)




**📂 Project Files**

index.html → Main HTML structure

styles.css → Styling & theme

script.js → Logic for time, weather, holidays, and countdown

holidays.json → List of Namibian public holidays




**⚙️ How It Works**

Clock & Date → Updates every second.

Weekend Countdown → Calculates days, hours, minutes, seconds left until Saturday midnight.

Weather →

Uses browser geolocation if allowed.

Falls back to Windhoek, NA by default.

Displays temperature, conditions, location, and feels-like temperature.

Uses emoji icons for weather representation.

Holidays → Loads from holidays.json (sorted and displayed with countdown days).




**🚀 Setup & Usage**

Clone or download the project files.

Open index.html in any modern browser.

(Optional) Add your OpenWeather API key in script.js:

const OPENWEATHER_API_KEY = "????????";


Ensure holidays.json is in the same directory for proper holiday loading.




**🎨 Features & UI Design**

Glassmorphism card layout with smooth hover effects.

Responsive design for mobile and desktop.

Dynamic animations (e.g., time pulse, weather icon tilt).




**📌 Future Improvements**

Add search functionality for custom cities.

Support multiple countries’ holidays.

Include theme switch (light/dark).



**📜 License**

This project is for educational purposes only under the WAD621S module at NUST.
