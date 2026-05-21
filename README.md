# PMO Intelligence Workspace

A complete offline-first PMO Operating System built as a single HTML file.

## Features
- 13 modules: Dashboard, Daily Log, Projects, Action Items, Meetings & MOM, Notes, Team Directory, Risk Register, Escalations, PMO Insights, Reports, Activity Log, Settings
- 100% offline — IndexedDB (Dexie.js), no server needed
- Fuzzy search across all data (Fuse.js)
- Excel export for all report types (SheetJS)
- JSON backup & restore
- Auto task creation from meeting action items
- Budget tracking, team workload, completion tracking
- Keyboard shortcuts: Ctrl+Shift+N quick capture, Esc to close

## Usage
Open `index.html` directly in any modern browser. No build step, no dependencies to install.

## Stack
- Vanilla JS + HTML + CSS (no framework)
- Dexie.js — IndexedDB wrapper (offline storage)
- SheetJS — Excel export
- Fuse.js — Fuzzy search

