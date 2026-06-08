
<p align="center"><h1 align="center">AI HABIT TRACKER (Frontend)</h1></p>
<p align="center">
	<em><code>❯ Build better habits with AI-powered insights, streak tracking, analytics, and personalized coaching.</code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/ibrahimthadathil/Ai-habit-tracker-frontend?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/ibrahimthadathil/Ai-habit-tracker-frontend?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/ibrahimthadathil/Ai-habit-tracker-frontend?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/ibrahimthadathil/Ai-habit-tracker-frontend?style=default&color=0080ff" alt="repo-language-count">
</p>
<p align="center"><!-- default option, no dependency badges. -->
</p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>
<br>

##  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Project Structure](#-project-structure)
  - [ Project Index](#-project-index)
- [ Getting Started](#-getting-started)
  - [ Prerequisites](#-prerequisites)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Testing](#-testing)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)

---

##  Overview

<code>❯ AI Habit Tracker is a modern habit-building application that helps users create, track, and improve daily habits through data visualization and AI-powered coaching.

The application provides:

- Habit creation and management
- Daily completion tracking
- Streak monitoring
- Weekly and monthly analytics
- AI-generated habit suggestions
- Personalized weekly reports
- Interactive dashboards and visualizations</code>

---

##  Features

<code>
### Habit Management
- Create, update, archive, and delete habits
- Categorize habits by type
- Daily completion tracking

### Analytics
- Weekly performance charts
- Monthly reports
- Heatmap visualizations
- Category-wise insights

### AI Features
- AI Habit Coach Chat
- AI Weekly Progress Reports
- Smart Habit Suggestions
- Morning Motivation Generator

### User Experience
- Responsive Design
- Dark/Light Theme
- Protected Routes
- Mobile Navigation</code>

---

## Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- Axios
- React Router

### Charts & Visualization
- Recharts

### Authentication
- JWT Authentication

### AI Integration
-  Gemini API

## Architecture

Frontend (React)
      ↓
Axios API Layer
      ↓
Node.js Backend
      ↓
MongoDB Database
      ↓
AI Service


##  Project Structure

```sh
└── Ai-habit-tracker-frontend/
    ├── README.md
    ├── eslint.config.js
    ├── index.html
    ├── package-lock.json
    ├── package.json
    ├── postcss.config.js
    ├── public
    │   ├── favicon.svg
    │   └── icons.svg
    ├── src
    │   ├── App.jsx
    │   ├── api
    │   ├── assets
    │   ├── components
    │   ├── context
    │   ├── index.css
    │   ├── main.jsx
    │   ├── pages
    │   └── utils
    └── vite.config.js
```


---
##  Getting Started

###  Prerequisites

Before getting started with Ai-habit-tracker-frontend, ensure your runtime environment meets the following requirements:

- **Programming Language:** JavaScript
- **Package Manager:** Npm


###  Installation

Install Ai-habit-tracker-frontend using one of the following methods:

**Build from source:**

1. Clone the Ai-habit-tracker-frontend repository:
```sh
❯ git clone https://github.com/ibrahimthadathil/Ai-habit-tracker-frontend
```

2. Navigate to the project directory:
```sh
❯ cd Ai-habit-tracker-frontend
```

3. Install the project dependencies:


**Using `npm`** &nbsp; [<img align="center" src="https://img.shields.io/badge/npm-CB3837.svg?style={badge_style}&logo=npm&logoColor=white" />](https://www.npmjs.com/)

```sh
❯ npm install
```




###  Usage
Run Ai-habit-tracker-frontend using the following command:
**Using `npm`** &nbsp; [<img align="center" src="https://img.shields.io/badge/npm-CB3837.svg?style={badge_style}&logo=npm&logoColor=white" />](https://www.npmjs.com/)

```sh
❯ npm run dev
```

## Environment Variables

Create a `.env` file:

```env
VITE_API_URL=http://localhost:5000
```
###  Testing
Run the test suite using the following command:
**Using `npm`** &nbsp; [<img align="center" src="https://img.shields.io/badge/npm-CB3837.svg?style={badge_style}&logo=npm&logoColor=white" />](https://www.npmjs.com/)

```sh
❯ npm test
```


---
##  Project Roadmap

```md
## Roadmap

- [x] Habit Tracking
- [x] Analytics Dashboard
- [x] AI Weekly Reports
- [x] Habit Suggestions
- [x] Authentication
```

## Related Repositories

Frontend:
https://github.com/ibrahimthadathil/Ai-habit-tracker-frontend

Backend:
https://github.com/ibrahimthadathil/Ai-habit-tracker-Backend
---

##  Contributing

- **💬 [Join the Discussions](https://github.com/ibrahimthadathil/Ai-habit-tracker-frontend/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/ibrahimthadathil/Ai-habit-tracker-frontend/issues)**: Submit bugs found or log feature requests for the `Ai-habit-tracker-frontend` project.
- **💡 [Submit Pull Requests](https://github.com/ibrahimthadathil/Ai-habit-tracker-frontend/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/ibrahimthadathil/Ai-habit-tracker-frontend
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/ibrahimthadathil/Ai-habit-tracker-frontend/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=ibrahimthadathil/Ai-habit-tracker-frontend">
   </a>
</p>
</details>

---

##  License

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

##  Acknowledgments

- List any resources, contributors, inspiration, etc. here.

---
