# Plan the Layout

This folder contains the layout instructions for the AI agent working on this project.

## Required project constraints

- Use only HTML and Tailwind CSS v4.
- Do not use React, Vue, or other frameworks.
- Use the official Tailwind CSS v4 build setup.
- Do not use `cdn.tailwindcss.com` or Tailwind CSS v3 instructions.
- Use semantic HTML elements such as `<header>`, `<nav>`, `<main>`, `<section>`, and `<table>`.
- Design mobile-first and adapt with Tailwind breakpoints such as `sm:`, `md:`, and `lg:`.
- Use Tailwind utility classes for styling. Do not add other CSS frameworks or custom CSS, except chart CSS if needed.
- Keep repeated components consistent, especially KPI cards.
- Do not add features or technologies that were not requested.

## Layout planning instructions

Before implementing the page, decide:

1. Whether the main structure should use a navbar, header, sidebar, or a combination.
2. How content should be divided into sections.
3. Whether top-level content should contain KPI cards.
4. Whether middle sections should display drivers, metrics, or supporting widgets.
5. Whether bottom sections should contain tables or lists.
6. Which patterns should be reusable, including cards, widgets, boxes, tables, and section layouts.
7. How the same components will adapt from mobile to tablet and desktop.

The exact dashboard content has not been specified. Do not invent business metrics, sample data, branding, chart types, or other domain-specific features. Implement only what the user specifies in the repository or later instructions.

## Responsive layout requirements

- Start with the smallest screen.
- Use responsive Tailwind utilities such as `sm:`, `md:`, and `lg:` as needed.
- Prefer Tailwind spacing, sizing, flexbox, and grid utilities over arbitrary pixel values.
- Prevent unintended horizontal overflow.
- Make tables or wide content usable on narrow screens.

## Semantic HTML and consistency

- Use appropriate semantic elements and a logical heading hierarchy.
- Use accessible labels for form controls.
- Keep repeated cards and similar elements visually consistent.
- Use consistent spacing, typography, borders, and component structure.
- Keep styling within Tailwind utilities, except for chart CSS if genuinely needed.

## Tailwind CSS v4 requirements

- Use the official Tailwind CSS v4 build process.
- Use `@import "tailwindcss";` in the Tailwind input stylesheet.
- Do not use `cdn.tailwindcss.com`.
- Do not use Tailwind CSS v3 setup instructions or the v3 `@tailwind base`, `@tailwind components`, and `@tailwind utilities` directives.
- Ensure the HTML references the generated stylesheet.

## Agent workflow

1. Read this folder before making changes.
2. Inspect the existing repository and preserve unrelated work.
3. Plan the layout and responsive behavior before implementing.
4. Create or update only the necessary files.
5. Build the project and fix setup or compilation errors.
6. Report the files changed and the commands needed to run the project.
7. Do not claim visual testing was completed unless it was actually performed.
