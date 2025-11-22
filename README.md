# NYC Motor Vehicle Collisions Dashboard

Interactive analytics dashboard for NYC motor vehicle collisions, covering 2012–2025. Explore trends, contributing factors, and casualty distributions across all five boroughs with maps and charts.

## Live Deployment

- Website: https://nyc-dataengineering.vercel.app/
- Final dataset: https://drive.google.com/file/d/1-5m8mupYnMcKXmXghCpq4euIjkSOyMki/view?usp=sharing

## Tech Stack

- Vite + React 18 + TypeScript
- Tailwind CSS + shadcn/ui (Radix UI)
- Recharts for charts, Leaflet for mapping
- React Router for routing

## Setup

- Prerequisites: Node.js 18+ and npm
- Install dependencies: `npm install`
- Start development server: `npm run dev` then open the local URL shown (default `http://localhost:5173`)
- Lint the project: `npm run lint`
- Build for production: `npm run build`
- Preview local production build: `npm run preview`

Notes:

- A sample subset is included at `public/data/nyc_collisions_sample_30k.csv` for quick local exploration.

## Deployment

- Current hosting: Vercel
- Typical deployment steps:
  - Push this repository to GitHub/GitLab
  - Import the project in Vercel and use the defaults:
    - Build command: `vite build`
    - Output directory: `dist`
  - Alternatively, use the Vercel CLI from the project root:
    - `npm run build`
    - `npx vercel deploy` (first time) or `npx vercel --prod`

## Team Contributions


- Moamen Alaa — built the website UI/UX and frontend implementation
- Mohamed Eldagla — data preparation and cleaning, exploratory data analysis (EDA)
- Mohamed Yasser — data integration and post-EDA consolidation

## Project Description

- Purpose: Provide an advanced traffic intelligence view of NYC collision data with interactive filters by borough, year, vehicle type, and contributing factors.
- Key features:
  - Borough-level casualty breakdowns and trend analysis
  - Interactive map and charts that update with filters
  - Export utilities for CSV/PDF snapshots

## How to Contribute

- Fork the repo and create feature branches
- Keep code style via `npm run lint`
- Open a pull request describing changes and screenshots where relevant
