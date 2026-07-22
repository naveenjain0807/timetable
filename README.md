# Timetable App

A React + TypeScript + Vite starter project for building a timetable/scheduling application.

## Current Functionality

- Vite-powered React application with TypeScript support
- Hot module replacement enabled via Vite
- Basic starter UI in `src/App.tsx`
- Styling using `src/App.css` and `src/index.css`
- Linting configured with `oxlint`
- Git repository initialized and the initial commit pushed to GitHub

## Planned Timetable Features

- Weekly timetable grid for days and time slots
- Timetable entry creation, editing, and deletion
- Filter entries by day or subject
- Responsive layout for desktop and mobile
- Accessibility improvements for keyboard and screen reader users
- GitHub Actions CI workflow for build validation
- Consistent linting and quality checks

## Getting Started

```bash
npm install
npm run dev
```

Open the local development URL shown by Vite to view the app.

## Available Scripts

- `npm run dev` - Start the Vite development server
- `npm run build` - Build the app for production
- `npm run lint` - Run Oxlint checks
- `npm run preview` - Preview the production build locally

## Project Structure

- `src/App.tsx` - Main application component
- `src/main.tsx` - App bootstrap and render entry
- `src/App.css` - App component styling
- `src/index.css` - Global styles
- `.github/` - GitHub-related configuration and workflows
- `.oxlintrc.json` - Oxlint configuration
- `package.json` - Project scripts and dependencies
- `tsconfig.json` - TypeScript configuration
- `vite.config.ts` - Vite configuration

## Notes

This repository currently contains the starter template and has been initialized with a GitHub remote. The next development steps are to replace the placeholder UI with the actual timetable interface and add the timetable-specific data model and interactions.
