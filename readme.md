# Currency Converter

This project is a dynamic and responsive currency converter web app. It allows users to view exchange rates, add new currency pairs, and search existing rates. The application is built using HTML, CSS, and JavaScript and emphasizes core concepts like DOM manipulation, fetch API, responsive UI design, and time-based logic.

## 📋 Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [File Structure](#file-structure)
- [Features in Detail](#features-in-detail)

---

## 🧭 Overview

The Currency Converter app provides a user interface to manage exchange rates. Users can:

- Add currency pairs with their exchange rates.
- View a table of rates.
- Search for specific exchange rates.
- See real-time market open/close status based on local time.

This project simulates a basic finance tool and demonstrates intermediate front-end development skills with interactive JavaScript logic.

---

## 🎯 Objectives

- Build a dynamic UI with JavaScript DOM manipulation.
- Fetch and process data from an external JSON file.
- Display real-time status updates using `setInterval`.
- Structure the layout responsively with clean design principles.
- Provide a functional search and add form experience.

---

## ✨ Features

- **Dynamic Exchange Rates Table**: Display exchange rates with real-time data updates.
- **Currency Addition**: Add new base-target currency pairs and store them in memory.
- **Exchange Rate Search**: Instantly look up rates between two currencies.
- **Market Status Banner**: Indicates if the financial market is currently open or closed (9 AM–5 PM).
- **Responsive Design**: Optimized for desktop and mobile screen sizes.
- **Background Imagery**: Styled with a financial-themed background for visual context.

---

## 🛠 Technologies Used

- **HTML5**: Structure and semantic layout.
- **CSS3**: Styling with Flexbox, responsive elements, and interactive tables.
- **JavaScript (ES6+)**: Application logic, fetch API, event handling, timers.

---

## ⚙️ Setup

To run the project locally:

```bash
git clone https://github.com/your-username/currency-converter.git
cd currency-converter
open index.html # Or open it using your preferred browser
```

Make sure you have internet access to load the external JSON from GitHub.

---

## 📁 File Structure

```
currency-converter/
├── index.html       # Main HTML structure
├── styles.css       # CSS styling
├── script.js        # JavaScript logic
├── currency-stock.png # Background image
└── README.md        # Project documentation
```

---

## 🧩 Features in Detail

### Add Currency Form

- Includes inputs for base currency, target currency, and rate.
- Validates and prevents duplicates.
- Updates the exchange table dynamically.

### Exchange Rates Table

- Displays fetched and user-added currency pairs.
- Organized with styling and alternating row colors for readability.
- Latest date is shown for each rate entry.

### Search Exchange Rate

- Allows users to search for a specific exchange rate.
- Displays the result or a message if the pair isn’t found.

### Market Status

- Banner fixed at the bottom of the screen.
- Automatically updates every minute based on local time.
- Highlights whether the market is currently open or closed.

### Responsive Design

- Centered layout with readable fonts and vibrant buttons.
- Mobile-first principles ensure usability across devices.
