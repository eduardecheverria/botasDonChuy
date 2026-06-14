# Artículos Vaqueros Don Chuy

Landing page for **Don Chuy** western goods store, built with Next.js, TypeScript, and Tailwind CSS.

## Requirements

- [Node.js](https://nodejs.org/) v18 or higher
- npm v9 or higher

## Installation

```bash
# 1. Clone or download the repository
git clone <repo-url>
cd don_chuy_next

# 2. Install dependencies
npm install
```

## Development

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available scripts

| Script | Description |
|---|---|
| `npm run dev` | Development server with hot reload |
| `npm run build` | Production build |
| `npm run start` | Production server (requires build first) |
| `npm run lint` | Lint the code with ESLint |

## Stack

- **Next.js** 16 — App Router
- **TypeScript** 5
- **Tailwind CSS** 4
- **ESLint** 9

## Project structure

```
don_chuy_next/
├── src/
│   └── app/
│       ├── layout.tsx      # Root layout
│       ├── page.tsx        # Home page
│       └── globals.css     # Global styles
├── public/                 # Static assets
├── next.config.ts
├── tsconfig.json
└── package.json
```
