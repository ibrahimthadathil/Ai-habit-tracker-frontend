# AI Habit Tracker (Frontend)

<p align="center">
  <em>Build better habits with AI-powered insights, streak tracking, analytics, and personalized coaching.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/ibrahimthadathil/Ai-habit-tracker-frontend?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
  <img src="https://img.shields.io/github/last-commit/ibrahimthadathil/Ai-habit-tracker-frontend?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
  <img src="https://img.shields.io/github/languages/top/ibrahimthadathil/Ai-habit-tracker-frontend?style=default&color=0080ff" alt="repo-top-language">
  <img src="https://img.shields.io/github/languages/count/ibrahimthadathil/Ai-habit-tracker-frontend?style=default&color=0080ff" alt="repo-language-count">
</p>

---

## Table of Contents

* [Overview](#overview)
* [Features](#features)
* [Tech Stack](#tech-stack)
* [Architecture](#architecture)
* [Project Structure](#project-structure)
* [Getting Started](#getting-started)

  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Environment Variables](#environment-variables)
* [Roadmap](#roadmap)
* [Related Repositories](#related-repositories)
* [Contributing](#contributing)
* [License](#license)
* [Author](#author)

---

## Overview

AI Habit Tracker is a modern habit-building application that helps users create, track, and improve daily habits through data visualization and AI-powered coaching.

The application provides:

* Habit creation and management
* Daily completion tracking
* Streak monitoring
* Weekly and monthly analytics
* AI-generated habit suggestions
* Personalized weekly reports
* Interactive dashboards and visualizations

---

## Features

### Habit Management

* Create, update, archive, and delete habits
* Categorize habits by type
* Daily completion tracking
* Track consistency and streaks

### Analytics

* Weekly performance charts
* Monthly reports
* Heatmap visualizations
* Category-wise insights
* Progress summaries

### AI Features

* AI Habit Coach Chat
* AI Weekly Progress Reports
* Smart Habit Suggestions
* Morning Motivation Generator

### User Experience

* Responsive Design
* Dark / Light Theme
* Protected Routes
* Mobile Navigation
* Real-time UI updates

---

## Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS
* Axios
* React Router

### Charts & Visualization

* Recharts

### Authentication

* JWT Authentication

### AI Integration

* Gemini API

---

## Architecture

```text
Frontend (React + Vite)
        ↓
Axios API Layer
        ↓
Node.js Backend
        ↓
MongoDB Database
        ↓
Gemini AI Service
```

---

## Project Structure

```text
Ai-habit-tracker-frontend/
├── public/
├── src/
│   ├── api/
│   ├── assets/
│   ├── components/
│   ├── context/
│   ├── pages/
│   ├── utils/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── README.md
├── package.json
└── vite.config.js
```

---

## Getting Started

### Prerequisites

Before getting started, ensure your environment has:

* Node.js
* npm

### Installation

Clone the repository:

```bash
git clone https://github.com/ibrahimthadathil/Ai-habit-tracker-frontend.git
```

Navigate to the project directory:

```bash
cd Ai-habit-tracker-frontend
```

Install dependencies:

```bash
npm install
```

### Usage

Start the development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview production build:

```bash
npm run preview
```

---

## Environment Variables

Create a `.env` file in the project root:

```env
VITE_API_URL=http://localhost:5000
```

---

## Roadmap

### Completed

* [x] Habit Tracking
* [x] Authentication System
* [x] Analytics Dashboard
* [x] AI Weekly Reports
* [x] Habit Suggestions
* [x] Dark Mode Support

### Upcoming

* [ ] Push Notifications
* [ ] Social Habit Challenges
* [ ] Achievement & Reward System
* [ ] Mobile Application

---

## Related Repositories

### Frontend

https://github.com/ibrahimthadathil/Ai-habit-tracker-frontend

### Backend

https://github.com/ibrahimthadathil/Ai-habit-tracker-Backend

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

## License

This project is licensed under the MIT License.

See the LICENSE file for details.

---

## Author

**Ibrahim Thadathil**

* MERN Stack Developer
* GitHub: https://github.com/ibrahimthadathil

---
