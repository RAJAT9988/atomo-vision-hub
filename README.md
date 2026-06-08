# Atomo Vision Hub

Enterprise AI surveillance dashboard by **Atomo Innovations Pvt Ltd**.

## Features

- Command Center with real-time stats and alerts
- Person, animal, inventory, and ANPR detection views
- Interactive 3D digital twin with camera streams
- Camera monitor, edge devices, AI models, and reporting

## Local development

Requirements: Node.js 18+ and npm.

```sh
git clone <YOUR_GIT_URL>
cd atomo-vision-hub-main
npm install
npm run dev
```

The app runs at `http://localhost:8080`.

## Build

```sh
npm run build
npm run preview
```

## Deploy

This project is configured for [Vercel](https://vercel.com). Connect your repository and deploy with:

- **Build command:** `npm run build`
- **Output directory:** `dist`

## Tech stack

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
- Three.js (digital twin)
