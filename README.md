🌾 AgriShield – Smart Crop Protection

AgriShield is a smart, farmer-friendly web application designed to help farmers monitor crop health, identify potential crop diseases and pests, understand environmental risks, and take practical management actions.

«🌱 Early Detection. Smarter Farming. Healthier Crops.»

---

🚀 Features

🔐 Farmer Authentication

- Farmer login using registered mobile number and password
- Create a new farmer account
- Password show/hide option
- Login validation
- Animated login and account-creation interface
- Login success animation
- Secure session stored on the device

📷 AI Crop Scanner

- Capture or select a crop image
- Analyze the selected crop
- Display:
  - 🌱 Crop name
  - 🦠 Disease/Pest detection
  - 🎯 Confidence
  - ⚠️ Severity
  - 🔍 Symptoms
  - 💡 Recommendation
- Displays the matched reference image when available
- Scan results can be saved as reports

The project includes an image-classification model integration using Hugging Face Transformers and an ONNX plant-disease model.

🌦️ Weather & Risk

- Temperature
- Humidity
- Rain chance
- Disease-risk information
- Weather forecast
- Crop-related environmental risk information
- Save weather information as a report

🐛 Pest Monitoring

- Monitor pest observations
- Track infestation severity
- Add and manage pest-related observations

🧠 Smart Advisory

AgriShield converts the latest crop-scan result into an easy-to-follow action plan.

It provides:

- Today's recommended actions
- Next 2 days' actions
- Symptoms
- Management recommendations
- Monitoring instructions
- Option to save the action plan

The advisory uses the latest completed scan and persists that information locally.

📈 Crop Health History

- View previous crop scans
- Track crop health trends
- Display scan date, crop, detection, confidence and severity
- Clear scan history when required

📁 Saved Documents

Users can save:

- Crop Scan Reports
- Weather & Risk Reports
- Management Action Plans

Saved documents can be viewed or deleted from the Documents section.

👤 Profile

- View farmer profile
- Edit farmer name
- Update mobile number
- Save profile information

🌐 Multiple Languages

The application supports:

- 🇬🇧 English
- 🇮🇳 Telugu
- 🇮🇳 Hindi

The interface includes translated navigation and application text.

🌙 Dark Mode

- Light mode
- Dark mode
- Responsive interface for mobile devices

✨ Dynamic UI

AgriShield includes:

- Animated login screen
- 3D card flip
- Floating particles
- Animated logo
- Smooth page transitions
- Animated dashboard cards
- Hover effects
- Button animations
- Progress-bar effects
- Toast notifications
- Responsive mobile layout

---

🛠️ Technologies Used

- HTML5 – Application structure
- CSS3 – Styling, responsive design and animations
- JavaScript – Application logic and interactions
- Font Awesome – Icons
- Hugging Face Transformers – Image-classification integration
- ONNX – Machine-learning model format
- LocalStorage – Local user, history and document data

---

📂 Project Structure

AgriShield/
│
├── index.html
├── style.css
├── script.js
└── README.md

If you are currently using a single HTML file, the project can also be run as:

AgriShield/
│
├── AgriShield.html
└── README.md

---

▶️ How to Run

Method 1 – Directly in Browser

1. Download or clone the project.
2. Open the HTML file.
3. Open it using Google Chrome or another modern browser.
4. Create an AgriShield account.
5. Login using the registered mobile number and password.
6. Explore the dashboard.

Method 2 – VS Code

1. Open the project folder in Visual Studio Code.
2. Open the HTML file.
3. Install the Live Server extension if required.
4. Right-click the HTML file.
5. Select Open with Live Server.

---

📱 Main Application Sections

Section| Purpose
🏠 Home| Dashboard and crop-health overview
📷 Scan| Crop image analysis
🌦️ Weather| Weather and crop-risk information
🐛 Pests| Pest observations and monitoring
🧠 Advisory| Crop-specific management action plan
📈 History| Previous crop scans and health trends
📁 Documents| Saved reports and action plans
👤 Profile| Farmer account information

---

💾 Data Storage

AgriShield uses browser LocalStorage for local application data such as:

- Farmer account information
- Latest crop scan
- Scan history
- Saved documents
- Profile information

For example, saved documents are stored locally using:

agrishieldDocuments

and the latest scan is persisted using:

agrishieldLatestScan

This means the current version is primarily a client-side prototype and does not require a separate backend database for its basic functionality.

---

🧪 Supported Crop/Disease Examples

The project contains example detection results for crops including:

- 🍅 Tomato
- 🥔 Potato
- 🌾 Rice
- 🌾 Wheat
- 🫑 Brinjal
- 🌱 Okra
- 🥜 Groundnut
- 🌽 Maize
- 🌿 Cotton

Example detections include Leaf Blast, Rust Risk, Shoot & Fruit Borer, Leaf Spot, Fall Armyworm Risk and other crop-health conditions.

---

🎯 Project Objectives

1. Help farmers identify crop problems at an early stage.
2. Make crop-health information easier to understand.
3. Provide practical management recommendations.
4. Help farmers monitor crop conditions over time.
5. Provide weather-related crop-risk information.
6. Maintain useful crop scan records.
7. Provide a simple and mobile-friendly farming interface.

---

🔮 Future Improvements

Future versions can include:

- ☁️ Real-time weather API
- 🗺️ GPS-based farm location
- 🤖 Improved disease-detection AI model
- ☁️ Cloud database
- 👨‍🌾 Farmer-to-expert communication
- 📊 Advanced crop analytics
- 🔔 Real-time disease and weather alerts
- 📱 Android application
- 🌍 More Indian regional languages
- 🔒 Server-side authentication
- 📡 Offline-first functionality

---

⚠️ Disclaimer

AgriShield is a project/prototype intended to demonstrate smart crop monitoring and decision-support features.

AI or simulated detection results should not be treated as a definitive agricultural diagnosis. Farmers should verify serious crop problems with qualified agricultural experts or locally recommended crop-protection guidance before taking major treatment decisions.

---

👨‍💻 Project

Project Name: AgriShield
Category: Smart Agriculture / AgriTech
Application Type: Web Application
Focus: Crop Health, Disease Detection, Pest Monitoring & Smart Advisory

---

🌱 Vision

«“Empowering farmers with smarter technology for healthier crops and better decisions.”»

---

⭐ If you like this project

Give the repository a ⭐ and share AgriShield with others interested in Smart Agriculture, AI, Web Development and AgriTech.
