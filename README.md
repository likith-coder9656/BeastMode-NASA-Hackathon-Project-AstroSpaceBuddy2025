# 🚀 AstroBuddy – Your Personal AI Space Companion

AstroBuddy is an AI-powered web application developed by **Team BeastMode (Likith V & Rohith) Ai & Data Science semester - 1** participating for the **NASA Space Apps Challenge**.
<br>
## Custom Challange Statement - "Create an interactive tool that help people explore NASA space data in an engineering and educational way" 

<br>
Link to the Hosted Website:- https://beastmode-hackathon-project1.figma.site/
<br>
What uniqueness does it hold when compared to other sites?<br>


All-in-one ecosystem – Instead of focusing on just a chatbot, or just a 3D solar system, AstroBuddy combines AI conversation, real-time NASA data, quizzes, and 3D visualization into one seamless platform.

AI-powered learning – The quiz generator powered by OpenAI isn’t just static questions—it adapts, educates, and explains answers with fun facts, making learning personalized.

Accessibility-first design – While many hackathon projects skip WCAG compliance, you’ve included screen-reader support, keyboard navigation, and mobile-first UI for inclusivity.

Engagement focus – Gamification (quizzes + scores), interactive 3D models, and live space weather make it more than a utility—it’s an experience.

---

## 🌌 Features

* **🧠 AstroBuddy AI Chatbot** – Conversational assistant powered by OpenAI, answering space-related questions with live NASA data.
* **☀️ Live Space & Weather Data** – Fetches real-time updates like Mars weather, Astronomy Picture of the Day (APOD), ISS position, and asteroid feeds.
* **🌍 3D Interactive Solar System** – Explore planets in a 3D model built with Three.js, with pop-up info (mass, temperature, moons, fun facts).
* **❓ Space Quiz Generator** – AI-powered quizzes for fun learning with multiple-choice and true/false formats, plus score tracking.
* **♿ Accessibility** – WCAG-compliant, mobile-first design with dark/light toggle and screen reader support.
* **😓 Application applicable only for copmuter display that includes desktop/laptop, mobile view- use desktop mode in broswer. Can be updated to responsive display in future...
---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript / React.js
* **Backend:** Python (Flask/Django) *(if needed for API routing)*
* **APIs:**

  * [NASA Open APIs](https://api.nasa.gov/) (APOD, NEO, ISS, Mars weather, etc.)
  * [OpenAI API](https://openai.com/) (quiz + chatbot enhancement)
* **3D Model:** Three.js
* **Design:** Responsive UI with modern animations

---

## 🔑 Example NASA APIs Used

* **APOD (Astronomy Picture of the Day):** `https://api.nasa.gov/planetary/apod`
* **Mars Weather:** `https://api.maas2.apollorion.com/`
* **ISS Location:** `http://api.open-notify.org/iss-now.json`
* **Asteroid Data (NeoWs):** `https://api.nasa.gov/neo/rest/v1/feed`

---

## 🚀 Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/likith-coder9656/BeastMode-NASA-Hackathon-Project-AstroSpaceBuddy2025.git
   cd (write the file name)
   ```

2. Install dependencies:

   ```bash
   npm install (required dependencies from terminal)
   ```

   *(If backend needed: set up Python environment and install Flask/Django)*

3. Create a `.env` file and add your API keys:

   ```env
   NASA_API_KEY=QnnTjHHwCZ5D3YmslB2kE10n5PiaMioKUH3GiKg2
   ```

4. Start the development server:

   ```bash
   npm start
   ```

---

## 🎯 Challenge Addressed

AstroBuddy tackles the **NASA Space Apps Challenge** theme of **“Artificial Intelligence & Data Science - Driven Solutions for Space Education”** by transforming raw NASA datasets into an interactive platform. It makes space data **accessible, educational, and engaging** for students, enthusiasts, and the general public.

---

## 👩‍🚀 Team BeastMode

* **Likith V** – Frontend & Backend with AI Integration & Data Visulization
* **Rohith** – Data Fetch/Collection & Data Visulization

---

## 📜 License

This project is free of license – feel free to use, modify, and contribute!

---

✨ *“AstroBuddy – Your AI-powered gateway to the universe.”*
