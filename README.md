# garden_buddy
it's just a prototype and is still under development
# 🌿 Garden Buddy

**Garden Buddy** is a user-friendly, AI-assisted gardening web application aimed at making plant care easy, accessible, and efficient — especially for the elderly and specially-abled. It provides features like plant monitoring, shopping, AI advice, reminders, and a digital journal, all in one place.

---

## 📁 Project Structure

garden-buddy/
│
├── index.html           → Login or landing page (optional)
├── home.html            → Main dashboard with feature cards
├── dashboard.html       → Plant health status, profile, theme/language toggle
├── shop.html            → E-commerce store to buy seeds, tools, fertilizers
├── cart.html            → Shopping cart and checkout page
├── advisor.html         → AI assistant for plant care tips
├── journal.html         → Daily plant journal (log and view entries)
├── reports.html         → Graphs for sunlight & moisture (Chart.js)
├── reminders.html       → Set watering and care reminders
├── identifier.html      → Upload image to identify plants
├── README.md            → Project documentation

---

## 🚀 Features

### 🌱 Dashboard (`dashboard.html`)
- View soil health, moisture level, and AI tips
- List of user’s plants and care summaries
- Toggle between light and dark modes
- Switch language (English, Hindi, Tamil)
- Access profile settings and password update

### 🛒 Garden Store (`shop.html`) & Cart (`cart.html`)
- Browse seeds, tools, fertilizers, etc.
- Add to cart buttons for each item
- View cart items and remove them
- Enter shipping details and place an order

### 🤖 AI Plant Advisor (`advisor.html`)
- Users can enter a care-related question
- Displays static suggestion (e.g., watering schedule, sunlight tips)
- Can be extended to use a real backend model

### 📓 Daily Journal (`journal.html`)
- Add a date and care notes (watering, sunlight, issues)
- See past entries dynamically on the same page
- Uses vanilla JS for form handling

### 📊 Reports (`reports.html`)
- Weekly soil moisture levels (line chart)
- Sunlight exposure trends (bar chart)
- Powered by Chart.js for smooth visuals

### ⏰ Reminders (`reminders.html`)
- Add text-based plant care reminders
- Reminders displayed in list format
- Simple, no-database setup for quick use

### 📷 Plant Identifier (`identifier.html`)
- Upload plant image to preview
- Displays a static example result (e.g., "This looks like Tulsi")
- Can be extended using ML image classification tools (e.g., TensorFlow.js)

---

## 💻 Tech Stack

- **HTML5 + CSS3 + JavaScript** (no frameworks)
- **Chart.js** for data visualization
- **Font Awesome** for icons
- Fully **static**, easily deployable to GitHub Pages or Netlify

---

## 🔧 Accessibility & UI/UX

- 🌐 Multilingual interface
- 🎨 Light/dark theme support
- 📱 Responsive across desktop and mobile
- 👵 Designed with elderly/specially-abled users in mind

---

## 🛠️ Future Improvements

- Integrate real AI advisor via OpenAI or other LLM APIs
- Implement image recognition for plant identification
- Add authentication and persistent user data (via Firebase or Node.js backend)
- Add dynamic cart, inventory, and order management system
- Make the app installable as a Progressive Web App (PWA)

---

## 📸 Screenshots (Optional)

You can add screenshots or screen recordings here:
- `home.html` – Central hub of navigation
- `shop.html` – Online garden store UI
- `reports.html` – Moisture & sunlight charts

---

## 📑 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute this software for personal or commercial use.

---

## 🙏 Acknowledgements

- Icons: [Flaticon](https://www.flaticon.com/)
- Charts: [Chart.js](https://www.chartjs.org/)
- Fonts & UI Inspiration: [Google Fonts](https://fonts.google.com/), [Dribbble](https://dribbble.com/)
- HTML & JS logic: Hand-written, fully responsive and educational

---

## 🧪 How to Run the Project

1. Download or clone the repository.
2. Open `home.html` in any web browser.
3. Navigate between pages using the UI (all internal `.html` links).
4. No setup required — this is a purely static front-end prototype.

---



---

🌼 Happy Gardening with **Garden Buddy**!
