# Basic Next.js App Deployment

A starter Next.js (App Router) app used as a sample for practicing deployments.

## Tech Stack

Next.js · React · TypeScript · Tailwind CSS

## Prerequisites

- Node.js and npm

## Installation & Usage

```bash
git clone https://github.com/KahafSameer/basic-next-app-deployment-.git
cd basic-next-app-deployment-
npm install
npm run dev        # http://localhost:3000
```

| Command | Description |
|---|---|
| `npm run dev` | Development server |
| `npm run build` | Production build |
| `npm run start` | Serve the production build (port 3000 by default) |
| `npm run lint` | Run ESLint |

## Deploying on a server

```bash
npm install
npm run build
npm run start
```

## Project Structure

```
app/        # layout.tsx, page.tsx, globals.css
public/     # static assets
```
