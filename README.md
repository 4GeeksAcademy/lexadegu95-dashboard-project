# Elevate Analytics

A responsive business analytics dashboard demonstration built with semantic HTML and locally compiled Tailwind CSS v4.

## Technology

The project uses HTML5, Tailwind CSS v4, and the official `tailwindcss` and `@tailwindcss/cli` packages. It does not use JavaScript, application frameworks, chart libraries, component libraries, or a Tailwind CDN. The revenue visualization is inline SVG.

## Project Structure

```text
index.html
package.json
plan-the-layout.md
src/input.css
dist/output.css
```

## Prerequisites

- Node.js 20 or newer
- npm

## Install

```bash
npm install
```

## Develop

Run the Tailwind watcher in one terminal:

```bash
npm run dev
```

In a second terminal, serve the static project:

```bash
python3 -m http.server 8000
```

In GitHub Codespaces, open the **Ports** panel, forward port `8000`, and open its forwarded URL.

## Production Build

```bash
npm run build
```

The minified stylesheet is written to `dist/output.css` and linked by `index.html`.

## Sample Data

All KPI values, chart points, traffic percentages, and order records are sample data for demonstration. This static dashboard does not connect to a live database or payment system.
