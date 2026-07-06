# Sanjana Onteru Portfolio

Personal portfolio website showcasing forward deployed AI engineering work, projects, and experience.

## Overview

This is a single-page portfolio application for Sanjana Onteru, built with React and TypeScript. It presents professional background, selected projects, work experience, education, certifications, and contact information. Site content is driven by a central configuration file (`src/data/site.ts`), making updates straightforward without touching layout components.

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- shadcn-ui (Radix UI components)
- React Router

## Features

- Hero, About, Projects, Experience, Education, and Contact sections
- Project cards with links to GitHub repositories
- Responsive layout with shadcn-ui component library
- Content managed via `src/data/site.ts`

## Getting Started

### Prerequisites

- Node.js and npm (or Bun)

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

### Production build

```bash
npm run build
npm run preview
```

## Project Structure

```
src/
  components/   # UI sections and shadcn components
  data/         # Site content (site.ts)
  pages/        # Route pages
  main.tsx      # App entry point
public/         # Static assets
```
