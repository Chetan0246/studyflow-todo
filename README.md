# StudyFlow

StudyFlow is a polished, student-focused productivity app built as a single dependency-free HTML file. It combines task planning, study sessions, progress tracking, and daily reflection in one lightweight interface.

## Features

- Create, edit, complete, and delete tasks
- Categories for Study, Personal, Project, and Health
- Priority levels, due dates, notes, and recurring tasks
- Subtasks with independent completion tracking
- Drag-and-drop task ordering
- Search, category filters, status filters, and sorting
- Monthly calendar with planned-task markers
- Pomodoro focus timer with 25, 50, and 5-minute modes
- Seven-day completion analytics chart
- Daily review with today-vs-yesterday comparison
- Reflection notes for recording what improved each day
- Focus mode for reducing distractions
- Command palette with keyboard shortcuts
- Undo after deleting a task
- JSON export/import backups
- Light and dark themes
- Responsive mobile-friendly layout
- Data persistence through `localStorage`

## Getting started

No build step, server, package manager, or dependencies are required.

1. Clone or download the repository.
2. Open `index.html` in a modern web browser.
3. Start adding tasks.

You can also open the file directly from the repository folder:

```text
index.html
```

## Keyboard shortcuts

| Shortcut | Action |
| --- | --- |
| `N` | Focus the new-task field |
| `/` | Focus search |
| `F` | Toggle focus mode |
| `Ctrl/Cmd + K` | Open the command palette |
| `Esc` | Close a modal or exit focus mode |

## Data and privacy

StudyFlow stores tasks, completion activity, theme preferences, and daily reviews locally in the browser using `localStorage`. Nothing is sent to a server.

Use **Export JSON** to create a portable backup. Use **Import JSON** to restore a backup on the same or another browser.

Clearing browser site data will remove locally stored app data, so export a backup first if the information is important.

## Project structure

```text
studyflow-todo/
├── index.html
└── README.md
```

The app intentionally remains a single-file project so it is easy to study, customize, and deploy as a static page.

## Learning goals

This project demonstrates:

- Semantic HTML and accessible form controls
- Responsive CSS layout and theme variables
- Vanilla JavaScript state management
- Browser storage with `localStorage`
- Canvas-based data visualization
- Drag-and-drop interactions
- Import/export using the File and Blob APIs
- Keyboard-first interaction design

## License

This project is provided for learning and personal use.
