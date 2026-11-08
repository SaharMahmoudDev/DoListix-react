# DoListix: Task Manager

A React task manager for organizing daily tasks with categories, priorities, due dates, and quick search.

![DoListix preview](https://raw.githubusercontent.com/SaharMahmoudDev/SaharMahmoudDev.github.io/main/images/dolistix-light.jpg)

**Live demo:** https://dolistix-app.pages.dev/

## Features
- Add, edit, and delete tasks
- Categories, priorities, and due dates
- Filter tasks and smart fuzzy search (Fuse.js)
- Drag-and-drop to reorder tasks
- Share tasks to WhatsApp, Telegram, Facebook, X, and Messenger
- Form validation with Formik and Yup
- Data saved in localStorage

## Tech Stack
React · Vite · Context API · Formik · Yup · Fuse.js · Material UI · Bootstrap · React Router

## Project Structure
```
src/
├── components/   # task card, filters, header, modal, ...
├── features/taskForm/
├── context/      # tasks, filters, categories providers
├── hooks/
└── utils/        # localStorage helpers
```

## Getting Started
```bash
npm install
npm run dev
```

## What I Learned
- Managing shared state with several Context providers
- Building reusable, validated forms with Formik and Yup
- Adding fuzzy search and drag-and-drop to a React app
