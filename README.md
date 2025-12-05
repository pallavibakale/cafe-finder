# Cafe Finder

A simple, user-friendly web app to discover cafes nearby, view details, and save favorites. Built to help people find cozy spots to work, relax, or meet friends.

## Table of contents

- [Features](#features)
- [Tech stack](#tech-stack)
- [Getting started](#getting-started)
- [Configuration](#configuration)
- [Development](#development)
- [Maintainer / Contact](#maintainer--contact)

## Features

- Search cafes by name, location, or tags
- View cafe details (address, opening hours, photos, rating)
- Save favorites and view them later
- Responsive UI for mobile and desktop
- (Optional) Map view showing cafe locations
- (Optional) OAuth or sign-in for saving user-specific favorites

## Tech stack

(Replace with the actual stack used by this repo. Example options shown below.)

- Frontend: React / Vue / Svelte / plain HTML/CSS/JS
- Backend: Node.js + Express / Flask / Django / Ruby on Rails / Serverless
- Database: PostgreSQL / MongoDB / SQLite
- Maps / Places: Google Maps API, Mapbox, OpenStreetMap, or similar

## Getting started

1. Clone the repo
   ```
   git clone https://github.com/pallavibakale/cafe-finder.git
   cd cafe-finder
   ```
2. Install dependencies
```
   # Example for Node.js
   npm install

   # Example for Python
   pip install -r requirements.txt
```
3. Configure environment variables

   Copy the example env file and update values:
```
   cp .env.example .env
   # then open .env and set API keys, database URL, etc.
```
4. Run the application
```
   # Example (Node.js)
   npm run dev

   # Example (React)
   npm start
```
   Open http://localhost:3000 (or the port your app uses)

## Configuration

- Add API keys (e.g., Maps or Places API) to .env
- Database connection string in .env
- Any other runtime configuration (CORS, allowed hosts, feature flags)

## Usage

- Use the search bar to find cafes by name or location
- Click a cafe to view details
- Add cafes to favorites for later viewing

## Development

- Create a feature branch:
```
  git checkout -b feature/your-feature
```
- Run linters and tests (if configured):
```
  npm run lint
  npm test
```
- Commit and open a Pull Request:
```
  git add .
  git commit -m "Add <short description>"
  git push origin feature/your-feature
```

## Maintainer / Contact

Maintainer: pallavibakale  
GitHub: https://github.com/pallavibakale
Email: bakalepallavi16@gmail.com
