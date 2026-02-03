# Digital Persona Generator

🚀 An AI-powered tool to generate digital personas using modern web technologies.

A small web app to create digital personas and moodboards using AI and image APIs. Generate character/persona descriptions, collect moodboard images, and iterate quickly to prototype user archetypes.

What it does
- Generate persona profiles (name, bio, traits, goals).
- Create moodboards or image grids for each persona using image APIs.
- Use AI-powered prompts to expand or refine personas.

Project goal and features
- Goal: Help designers and product teams prototype realistic user personas quickly.
- Main features:
  - Persona generation (AI-driven text output)
  - Moodboard / image suggestions (Unsplash or similar)
  - Save and export persona data for sharing

Tech stack
- Frontend: React (JavaScript)
- Build tools: npm / Node.js
- APIs: Groq (for content queries) and Unsplash (for images) — or similar image APIs
- Optional: backend or serverless endpoints for proxying API requests

Local setup

Prerequisites
- Node.js (LTS recommended)
- npm (comes with Node.js)

Clone the repo
```bash
git clone https://github.com/<your-username>/digital-persona.git
cd digital-persona
# if the app lives in a web/ subfolder:
# cd web
```

Install dependencies
```bash
npm install
```

Environment variables
- Create a .env file in the project root (or the web/ folder if applicable).
- Example .env (do NOT commit secrets):
```
# .env.example
REACT_APP_UNSPLASH_ACCESS_KEY=
REACT_APP_SANITY_PROJECT_ID=
REACT_APP_API_BASE_URL=
```

Run the project locally
```bash
npm run dev
# or
npm start
```

Folder structure (overview)
- src/ — main source code
  - src/components/ — UI components
  - src/pages/ or src/views/ — page-level components or routes
  - src/styles/ — CSS or global styles
  - src/api/ — API helper functions
- public/ — static assets (images, favicon)
- scripts/ or server/ — optional backend or helpers
Note: Adjust paths to match this repo's exact layout.

Basic contribution guidelines (beginner-friendly)
1. Fork the repository on GitHub.
2. Clone your fork:
```bash
git clone https://github.com/<your-username>/digital-persona.git
cd digital-persona
```
3. Create a branch for your change:
```bash
git checkout -b feat/short-description
```
4. Commit message format (simple convention):
```
feat(component): brief description
fix(api): fix details
docs(readme): improve intro
```
5. Push your branch and open a Pull Request to main. In the PR:
- Describe what you changed and why
- Reference any related issue (if applicable)
- Keep changes small and focused

Need help?
- Open an issue with details of the problem and what you tried.
- Add screenshots or error logs when relevant.

Thank you for contributing — small improvements matter!
