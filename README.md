
TallyPal is a mobile application designed for tally clerk staffs working in logistics and manufacturing environments, such as cement plants or warehouses. The app provides an intuitive, user-friendly platform to ensure accurate and real-time tracking of time registrations, truck movements, and inventory data
 TallyPal

📦 TallyPal is a logistics and manufacturing helper app for tally clerks.  
It allows clerks to record **time registrations, truck movements, and inventory data** with ease.

---

🚀 Features
- User login & authentication
- Track time registrations (shifts, breaks)
- Log truck arrivals and departures
- Manage inventory (in/out)
- Generate simple reports

---

 🛠 Tech Stack
- Frontend: React Native / React.js
- Backend: Node.js (Express)
- Database: PostgreSQL (or SQLite for dev)

---
TallyPal-mobile/
├─ App.js
├─ package.json
├─ app.json
└─ components/
├─ RegistrationForm.js
└─ RegistrationsList.js


TallyPal-server/
├─ package.json
├─ index.js
├─ db.js
└─ routes/
└─ registrations.js
{
"name": "tallypal-mobile",
"version": "0.1.0",
"main": "node_modules/expo/AppEntry.js",
"scripts": {
"start": "expo start",
"android": "expo run:android",
"ios": "expo run:ios"
},
"dependencies": {
"expo": "~48.0.0",
"react": "18.2.0",
"react-native": "0.71.8",
"axios": "^1.4.0"
}
}
## 📂 Project Structure
