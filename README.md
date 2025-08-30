# 🚀 AI Career Assistant

🛠️ Built With
<p align="center"> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/> <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/> <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/> </p>
📌 What the project does

The AI Career Assistant is a web app that generates tailored job applications:

Users fill out a profile questionnaire (experience, education, strengths, skills).

They paste a job description.

The app uses AI to:

Extract key requirements (skills, responsibilities, keywords).

Generate a cover letter and optimized CV bullets.

Show a keyword coverage score.

# 💡 Why the project is useful

- Saves time by auto-tailoring applications.

- Helps highlight relevant experience and skills.

- Produces professional, ATS-friendly documents.

- Reduces stress and increases interview chances.

# 🚀 Getting Started
### Prerequisites

- Node.js (>= 18)

- npm or pnpm

- OpenAI API key

# Installation
### Clone the repo
- git clone https://github.com/OhjelmistoprojektiAiAssistant/ai-career-assistant.git
- cd ai-career-assistant

### Install dependencies
- npm install

### Setup environment variables
- cp .env.example .env

## Environment Variables (.env)
- DATABASE_URL="file:./dev.db"   # SQLite for development
- OPENAI_API_KEY=your_openai_key_here
- JWT_SECRET=your_secret_key

## Database Setup
- npx prisma migrate dev

## Run Development Server
- npm run dev


Open http://localhost:3000
 in your browser.

## ❓ Getting Help

- Read project docs in /docs.

- Check per-sprint README files for details. //-> Filled in later

- Open a GitHub issue if you need support. // ->  Filled in later

# 👥 Maintainers & Contributors

### Maintainers: Bashkim Grepi, Arjon Dragusha, Ardian Dragusha 2nd Year students @University of applied scienses Haaga-Helia

### Contributors: Bashkim, Arjon, Ardian
