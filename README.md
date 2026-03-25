# 🚀 Auto UI ↔ API Checker

## 📌 Overview

A testing tool that automatically interacts with the UI, extracts displayed data, and validates it against API responses to ensure consistency and accuracy between frontend and backend.

---

## 🎯 Key Features

* 🔄 Automates UI interactions (clicks, inputs, navigation)
* 📊 Extracts dynamic data directly from the UI
* 🔗 Fetches and parses API responses
* ⚖️ Compares UI data with API data
* 🚨 Highlights mismatches and inconsistencies

---

## 🎥 Demo Video

👉 https://drive.google.com/file/d/1BN8CwwTiRDsGvfddMt-ex5FSrgtyjHgm/view?usp=sharing

---

## ⚙️ Configuration & Execution
<img width="650" height="800" alt="Untitled" src="https://github.com/user-attachments/assets/807e2d4a-21d8-461c-a4d6-c0acf627f743" />

**(1) Login URL** - The URL of the login page where the tool performs authentication  
**(2) Main URL** - The main page after login, where UI data extraction begins  
**(3) End Point API** - The API endpoint used to fetch backend data for comparison  
**(4) User Name** - The username for login  
**(5) Password** - The password for login  
**(6) Token (optional)** - Authentication token (if required by the API). Can be left empty  
**(7) Use filter** - Enable or disable filters to limit the scope of data being tested. When enabled, additional filter options (10) will be displayed    
**(8) Enable scroll before hover (px)** - Scrolls the page before hovering over elements to ensure they are visible  
**(9) Auto click** - Automatically performs click actions based on configured selectors  
**(10) Filter options** - Filtering conditions to narrow down UI data for more accurate testing  
**(11) Auto click selector input** - Input selector, text, or XPath for automated click actions  

<img width="650" height="800" alt="image" src="https://github.com/user-attachments/assets/26f62bec-c0cd-4706-b994-3d77868ffcc5" />

**(12) Add mapping** - Add a new row to define mapping between API data and UI elements  
**(13) Mapping row** - Configure how API fields are matched with UI data (selector/label, data type, options)  
**(14) Actions (Run / Clear / Copy / Export / Import)** - Execute test, reset data, copy results, import/export configurations  
**(15) Result output** - Displays comparison results between UI data and API responses  

---

## 🛠️ Tech Stack

* JavaScript
* Node.js
* HTML/CSS

---

## 💡 Use Cases

* Validate UI data against backend APIs
* Detect data mismatch bugs quickly
* Support QA automation workflows

---

## ⚠️ Note

Due to deployment environment limitations (such as lack of browser support for automation tools like Playwright), the full functionality cannot be executed in a live hosted environment. Therefore, this repository is provided for demonstration purposes only.
