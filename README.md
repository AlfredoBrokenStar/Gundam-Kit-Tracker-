# Gundam Kit Tracker

**Track, organize, and showcase your Gundam model kit collection.**

---

## Overview

Gundam Kit Tracker is a personal collection manager for Gundam plastic model (Gunpla) enthusiasts. Catalog your kits by grade, series, and build status — from backlog to fully completed display pieces. Whether you're tracking a handful of High Grades or hundreds of Master Grades and Perfect Grades, this app keeps your collection organized.

## Features

- **Collection Catalog** — Add kits with details like grade (HG, RG, MG, PG, SD), series, scale, and release year
- **Build Status Tracking** — Mark kits as *Backlog*, *In Progress*, *Built*, *Painted*, or *Displayed*
- **Wishlist** — Keep a list of kits you plan to purchase
- **Search & Filter** — Quickly find kits by name, grade, series, or status
- **Statistics Dashboard** — See collection breakdowns by grade, status, and timeline
- **Image Support** — Attach photos of your completed builds

## Planned Tech Stack

| Layer       | Technology              |
|-------------|-------------------------|
| Frontend    | React + TypeScript      |
| Styling     | Tailwind CSS            |
| Backend     | Node.js / Express       |
| Database    | SQLite (local-first)    |
| Build Tool  | Vite                    |

## Kit Grades Reference

| Abbreviation | Grade                | Scale  |
|--------------|----------------------|--------|
| SD           | Super Deformed       | N/A    |
| HG           | High Grade           | 1/144  |
| RG           | Real Grade           | 1/144  |
| MG           | Master Grade         | 1/100  |
| PG           | Perfect Grade        | 1/60   |
| MGEX         | Master Grade Extreme | 1/100  |

## Project Structure (Planned)

```
Gundam-Kit-Tracker/
├── public/
├── src/
│   ├── components/     # React UI components
│   ├── pages/          # Route pages
│   ├── hooks/          # Custom React hooks
│   ├── db/             # Database schema & queries
│   ├── types/          # TypeScript type definitions
│   └── utils/          # Helper functions
├── package.json
├── tsconfig.json
├── tailwind.config.js
└── vite.config.ts
```

## Getting Started

> **Note:** This project is in early development. Setup instructions will be added as the codebase is built out.

```bash
# Clone the repository
git clone https://github.com/AlfredoBrokenStar/Gundam-Kit-Tracker-.git
cd Gundam-Kit-Tracker-

# Install dependencies (coming soon)
npm install

# Start development server (coming soon)
npm run dev
```

## Roadmap

- [x] Initialize repository
- [ ] Set up project scaffolding (Vite + React + TypeScript)
- [ ] Design database schema for kits
- [ ] Build core CRUD operations for collection
- [ ] Implement search and filtering
- [ ] Add build status workflow
- [ ] Create statistics dashboard
- [ ] Add image upload support
- [ ] Wishlist management
- [ ] Export/import collection data

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is open source. License TBD.
