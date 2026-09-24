# AURA — Holistic Health, Fitness & Mental Care Platform

> A production-grade, Apple Fitness+ inspired wellness platform combining physical vitality tracking, nutrition planning, and dedicated psychiatric care into a high-performance single-page web app.


---

## 🔗 Live Application
Experience the live deployed application here: **[AURA Live on Netlify](https://aura-nishant.netlify.app/)**

---

## 📌 Overview
**AURA** is designed to eliminate the boundary between physical conditioning and cognitive wellness. Drawing inspiration from the sleek, high-contrast visual architecture of watchOS and Apple Fitness+, the application delivers real-time activity telemetry, live workout guidance, precision macro tracking, and structured mental health intervention without external dependencies or heavy frameworks.

The entire frontend experience—comprising interface structures, reactive state changes, vector animations, and local persistence—is consolidated in a clean, self-contained architecture.

---

## 🚀 Key Modules & Features

* **Apple-Grade Concentric Rings:** Custom pure SVG concentric rings tracking Move (caloric expenditure), Exercise (active duration), and Stand/Recovery metrics with reactive stroke animations.
* **Live Workout HUD:** Interactive workout execution modal featuring a real-time elapsed timer, dynamic simulated heart rate telemetry (BPM), and continuous calorie calculation.
* **Precision Calorie & Macro Engine:** Visual caloric budget counter, interactive macro split bars (Protein, Carbohydrates, Fats), an interactive 8-stage hydration tracker, and dynamic meal logging.
* **Dual-Channel Psychiatric Care Suite:**
  * **Aura AI Copilot:** Cognitive behavioral prompts paired with an interactive CSS box-breathing meditation module.
  * **Clinical Telehealth Simulator:** Simulated secure consultation interface with a verified neuropsychiatrist profile for immediate intake assessment.
* **Zero-Backend Persistence:** Seamless client-side state caching using `localStorage` to preserve workouts, nutrition inputs, and mental check-ins between browser reloads.

---

## 🛠️ Architecture & Tech Stack

This project was built intentionally without complex build chains, package managers, or frontend libraries to guarantee instant load times and pure web standard execution:

* **Markup:** Semantic HTML5
* **Styling:** Vanilla CSS3 (Custom properties, glassmorphism, responsive grid/flex layouts, CSS keyframe animations)
* **Scripting:** Vanilla JavaScript (ES6+ DOM manipulation, SVG math, state handlers)
* **Visual Telemetry:** Pure SVG (Concentric activity gauges, data rings)
* **Iconography:** Lucide Icons (CDN)
* **Typography:** Inter (via Google Fonts)
* **Deployment:** Netlify

---

## 💻 Local Setup

Because the application is completely self-contained, no `npm install` or local server environment is strictly required.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git)
   cd YOUR_REPOSITORY_NAME
