# Elevate Analytics Layout Plan

## Structure

- A semantic sidebar contains product branding, horizontally scrollable mobile navigation, the Jordan Davis workspace profile, and a desktop-only reports prompt.
- The main area starts with a workspace breadcrumb, Overview heading, reporting-period control, and New Order link.
- Key Metrics contains four similarly structured KPI articles in one mobile column, two columns at `sm:`, and four at `xl:`.
- Performance contains a revenue article with an accessible inline SVG line chart and a traffic-source article; the articles stack on mobile and use a two-plus-one grid at `xl:`.
- Recent Orders contains a semantic table inside a horizontal overflow wrapper, followed by the demonstration footer.

## Responsive and Accessibility Notes

- Use mobile-first Tailwind utilities and `sm:`, `md:`, `lg:`, and `xl:` breakpoints.
- Keep cards consistent, use semantic landmarks and headings, label the period control, preserve visible focus indicators, and provide chart title/description and table caption.
- Keep navigation anchors connected to real dashboard sections or metrics.
- Identify every metric and record as sample data; do not imply a live data connection.

## Technology

Use semantic HTML5 and Tailwind CSS v4 compiled locally with the official `tailwindcss` and `@tailwindcss/cli` packages. Use inline SVG for the revenue chart. Do not add JavaScript, frameworks, external CSS libraries, or CDN stylesheets.
