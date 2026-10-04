# SafeCampus AI

<p align="center">
  <img src="https://img.shields.io/badge/AI-Scam%20Detection-00D1FF?style=for-the-badge&logo=google&logoColor=white" alt="AI Scam Detection" />
  <img src="https://img.shields.io/badge/TypeScript-98.3%25-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Powered%20by-Gemini-8A2BE2?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Gemini" />
</p>

<p align="center">
  <strong>AI-powered digital safety for students, interns, and job seekers.</strong>
</p>

<p align="center">
  SafeCampus AI helps protect students from internship, job, scholarship, and phishing scams by analyzing suspicious messages, screenshots, links, and senders using advanced AI.
</p>

<hr />

## ✨ Why SafeCampus AI?

Students often face high-pressure recruitment messages, fake scholarship offers, spoofed university portals, and social engineering scams. SafeCampus AI acts like a smart digital bodyguard—quickly detecting suspicious content and explaining the risk in plain, actionable language.

It helps users:

- Detect scam patterns in messages and screenshots
- Evaluate suspicious links and sender identities
- Get step-by-step safety recommendations
- Learn how scams work before they become costly mistakes
- Report and track scam trends in a community-aware database

<hr />

## 🧠 Core Features

### 1) AI Scam Scanner
Detect scam risk in:

- WhatsApp / Telegram text messages
- Email content
- Chat screenshots
- Suspicious links
- Fake sender identities

The system uses Gemini AI to assess content, infer scam intent, explain the warning, and recommend next steps.

### 2) AI Scam Advisor
A conversational assistant that helps users answer questions like:

- "Is this internship legit?"
- "Why does this email look fake?"
- "What should I do if I clicked a suspicious link?"

### 3) Threat Database
Browse a growing scam registry with:

- detected scam patterns
- reported examples
- risk levels
- community-driven insights

### 4) Safety Education Hub
Learn about:

- link verification
- phishing red flags
- job safety checks
- urgency-based scam tactics

### 5) Real-time Security Dashboard
Track scam activity through stats and incoming alerts, helping users understand what digital threats are trending right now.

<hr />

## 🏗️ Tech Stack

- React 19 + TypeScript
- Vite for fast frontend development
- Express backend
- Tailwind CSS for styling
- Google Gemini AI for scam analysis and chat
- SQLite for local data persistence
- Lucide icons + motion-based UI transitions

<hr />

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm or pnpm
- A Gemini API key

### 1) Clone the repo

```bash
git clone https://github.com/qianyi-11/SAFE-CAMPUS-AI.git
cd SAFE-CAMPUS-AI
```

### 2) Install dependencies

```bash
npm install
```

### 3) Configure environment variables

Create a `.env` file in the project root using the example:

```bash
cp .env.example .env
```

Then update the values:

```env
GEMINI_API_KEY="your_gemini_api_key"
APP_URL="http://localhost:3000"
```

> The app expects Gemini credentials to be available at runtime for AI-powered scanning and chat features.

### 4) Run the app

```bash
npm run dev
```

This will start the project locally and make the app available in your browser.

<hr />

## 📦 Available Scripts

```bash
npm run dev     # start the development server
npm run build   # build the production bundle
npm run preview # preview the production build
npm run lint    # TypeScript type-check
npm run clean   # remove the dist folder
```

<hr />

## 🧩 Project Structure

```text
SAFE-CAMPUS-AI/
├── src/                # React frontend and app logic
├── server.ts           # Express API server
├── .env.example        # Example environment configuration
├── index.html          # app entry
├── package.json        # project scripts and dependencies
├── tsconfig.json       # TypeScript config
├── vite.config.ts      # Vite configuration
├── README.md           # project documentation
└── metadata.json       # app metadata
```

<hr />

## 🔒 Safety First

SafeCampus AI is designed to help people make informed decisions, not panic. The platform promotes:

- caution before clicking unknown links
- verification before accepting job or scholarship offers
- awareness of digital fraud tactics
- informed action when something feels suspicious

<hr />

## 🎯 Mission

SafeCampus AI exists to protect students and early-career professionals from digital deception by combining AI-powered detection, clear educational guidance, and proactive scam awareness.

<hr />

## 🤝 Contributing

Contributions are welcome. If you'd like to improve the platform, add new scam patterns, improve the AI prompts, or enhance the UI:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request

<hr />

## 📜 License

This project is currently distributed without a formal license declaration. If you plan to reuse or distribute it publicly, it is recommended to add an appropriate open-source license.

<p align="center">
  <strong>Stay alert. Stay informed. Stay safe.</strong>
</p>
