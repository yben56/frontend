# Frontend Test Project (Vue 3 + Vite)

## Tech Stack
- Vue 3
- Vite
- TypeScript (optional)
- Vitest (planned)

---

## Setup

```bash
npm install
npm run dev
```

http://localhost:5173

---

## Build

```bash
npm run build
npm run preview
```

Output:
dist/

---

## Env

Use Vite env variables only (VITE_)

Files:
- .env.development
- .env.production
- .env.example (committed)

Example:

VITE_API_BASE_URL=http://localhost:8000
VITE_SITE_URL=http://localhost:5173

---

## Project Structure

```bash
frontend/
├── node_modules
├── dist
├── public/
├── src/
│   ├── components/
│   ├── views/
│   ├── composables/
│   ├── stores/
│   ├── utils/
│   ├── router/
│   ├── assets/
│   └── main.ts
│
├── e2e
├── tests/
│   ├── components/
│   ├── intergration/
│   └── unit/
│
├── index.html
├── vite.config.ts
├── tsconfig.json
├── package.json
│
├── /.git (hidden)
├── .gitignore
│
├── .github/workflows/
│   ├── cd.yml
│   └── ci.yml
│
├── .env.example
├── .env.development
├── .env.production
│
├── .dockerignore
├── Dockerfile.dev
├── Dockerfile.prod
│
└── README.md
```

---

## Scripts

npm run dev
npm run build
npm run preview
npm run test

---

## Docker

Not implemented yet
