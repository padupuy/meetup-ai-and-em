# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Slidev presentation for a French meetup talk about AI in Engineering Management. The presentation uses Vue.js-based Slidev framework with a custom ekino company theme.

## Essential Commands

```bash
# Install dependencies (using pnpm)
pnpm install

# Start development server (opens browser at localhost:3030)
pnpm dev

# Build for production (outputs to dist/)
pnpm build

# Export presentation to PDF/PNG
pnpm export
```

## Project Architecture

### Content Structure
- **Main presentation:** `slides.md` - The primary presentation content in Markdown/Slidev format
- **Additional slides:** `pages/` directory for imported or supplementary slide decks
- **Vue components:** `components/` for custom interactive elements
- **Code snippets:** `snippets/` for TypeScript/JavaScript examples used in slides

### Key Files
- `slides.md` - Main presentation content with Slidev-specific markdown syntax
- `pitch.md` - Raw content and speaker notes for the presentation
- `slides-overview.md` - Presentation structure and flow guide
- `prompt.md` - AI instructions used to generate initial slide content

### Slidev-Specific Syntax
- Slides are separated by `---`
- Front matter configuration at the top of slides.md
- Vue components can be embedded directly in markdown
- Uses MDC (Markdown Component) syntax for advanced features
- Theme: `@ekino/slidev-theme-ekino` provides company branding

## Development Workflow

1. Edit `slides.md` for content changes
2. Use `pnpm dev` to preview changes with hot-reload
3. Custom Vue components go in `components/` directory
4. Code examples should be placed in `snippets/` for better organization
5. Build with `pnpm build` before deployment

## Deployment Configuration

Both Vercel and Netlify are configured:
- Build command: `npm run build`
- Output directory: `dist`
- Node version: 20 (for Netlify)
- SPA routing properly configured in both platforms