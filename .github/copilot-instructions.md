# Project Guidelines

## Overview
Mona Mayhem is a workshop template for building a GitHub contribution battle arena using Astro and GitHub Copilot. It demonstrates modern web development with Astro's server-side rendering and TypeScript.

## Build and Test
- `npm run dev` — Start development server
- `npm run build` — Create production build
- `npm run preview` — Preview production build

## Architecture
- **Framework**: Astro v5 with Node.js adapter for server-side rendering
- **Language**: TypeScript with strict mode enabled
- **Routing**: File-based routing in `src/pages/`
- **API**: Dynamic routes in `src/pages/api/` for server-side data fetching

## Conventions
- Use `.astro` files for pages and components
- Dynamic API routes use `[param].ts` syntax with `export const prerender = false`
- Type API handlers with `APIRoute` interface
- Prefer server output mode for dynamic content

## Astro Best Practices
- Leverage Astro's component islands for interactive elements
- Use `---` frontmatter for component logic
- Import components and utilities at the top
- Handle dynamic data fetching in API routes, not components