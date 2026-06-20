# 🎬 Movies Intergalactic

A movie search app that pulls live data from the OMDB API — search any title and get back its poster, plot, genre, cast, writer/director, runtime and release info, rendered as clean card-based UI.

**Status:** 🚧 In active development — built as a personal project to practice component architecture, state management, and third-party API integration. See the [Roadmap](#roadmap) below for what's planned next.

## Features

- 🔍 Search for any movie by title
- 🖼️ Displays poster, plot summary, and rating/runtime/release badges
- 🎭 Genre, cast, writer, and director shown as tagged badges
- ⚡ Built with React 19 + Vite for fast dev/build

## Tech Stack

- **React 19** — UI and component state
- **Vite** — dev server and build tooling
- **Tailwind CSS 4** + **DaisyUI** — styling and UI components
- **OMDB API** — movie data source


## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- An OMDB API key — get a free one at [omdbapi.com/apikey.aspx](https://www.omdbapi.com/apikey.aspx)

### Installation

```bash
# Clone the repo
git clone https://github.com/Nik-Fle/movies-intergalactic.git
cd movies-intergalactic

# Install dependencies
npm install
```

### Environment Variables

This app needs an OMDB API key to fetch movie data. Create a `.env` file in the project root:

```
VITE_OMDB_API_KEY=your_api_key_here
```

> Vite only exposes env variables prefixed with `VITE_` to the front end, and reads them via `import.meta.env.VITE_OMDB_API_KEY`. Add `.env` to your `.gitignore` so your real key never gets committed.

### Run locally

```bash
npm run dev
```

Then open the local URL Vite prints in your terminal (usually `http://localhost:5173`).

## Roadmap

Planned additions:

- [ ] Languages and country metadata
- [ ] Awards info
- [ ] Side-by-side ratings comparison (IMDB, Rotten Tomatoes, Metacritic)
- [ ] Personal Accounts 
- [ ] To Watch List 
- [ ] Media type filter (movie / series / episode)
- [ ] Box office figures

## Acknowledgments

Movie data provided by the [OMDB API](https://www.omdbapi.com/).