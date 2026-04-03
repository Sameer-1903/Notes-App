# Noted. — React Notes App

A clean, minimal notes app built with React + Vite.

## Features
- Create, edit, and delete notes
- Pin important notes to the top
- Color-code notes (5 themes)
- Search across all notes in real time

## Getting Started

```bash
npm install
npm run dev
```

## Folder Structure

```
noted-app/
├── public/
│   ├── index.html
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── NotesApp.jsx      # Main app shell + state management
│   │   ├── NoteCard.jsx      # Individual note card (read view)
│   │   └── NoteEditor.jsx    # Inline note editor (edit view)
│   ├── styles/
│   │   ├── index.css         # Global reset & base styles
│   │   └── notes.module.css  # Component-scoped CSS modules
│   ├── constants.js          # Color palette & initial seed data
│   ├── utils.js              # Helper functions (date formatting etc.)
│   ├── App.jsx               # Root component
│   └── main.jsx              # React DOM entry point
├── .gitignore
├── package.json
├── vite.config.js
└── README.md
```

## Next Steps (Backend + DB)
- Add Express/Node.js REST API
- Connect to PostgreSQL or MongoDB
- Replace in-memory state with API calls
- Add user authentication
