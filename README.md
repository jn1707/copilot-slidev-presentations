# Copilot Slidev Presentations

Create presentations fast **as code** using Markdown-based format and Slidev with GitHub Copilot CLI as your co-author.

This repository demonstrates a workflow where GitHub Copilot CLI can generate complete, structured slide decks in minutes, using:
- a Slidev template
- raw notes
- explicit agent instructions via AGENTS.md

---

## Why This Exists

Writing slides is often:
- time-consuming
- repetitive
- hard to iterate on quickly

By treating presentations as code and giving GitHub Copilot CLI clear structure and constraints, drafting slides becomes fast, reproducible, and surprisingly reliable.

This workflow was designed for real-world scenarios where you need a **working presentation quickly**, not polished marketing slides.

---

## The Workflow

```text
notes.md + slides.md template + AGENTS.md
            ↓
   GitHub Copilot CLI
            ↓
   Working presentation
```

## Quick Start

### Prerequisites
- Node.js (v18 or higher)
- pnpm (recommended) or npm

### Starting a Presentation

```bash
# Navigate to a presentation folder
cd example

# Install dependencies (first time only)
pnpm install

# Start the dev server
pnpm dev
```

The presentation will open at `http://localhost:3030` (or similar).

### Creating a New Presentation

```bash
# Copy the template
cp -r template "My New Presentation"
cd "My New Presentation"

# Install dependencies
pnpm install

# Start editing slides.md
pnpm dev
```
<details>

## Exporting Presentations

### Export to PDF

```bash
# Build and export to PDF
pnpm export

# Or specify output name
pnpm export --output my-presentation.pdf
```

The PDF will be created in the `./slides-export.pdf` (or your specified name).



### Export to PowerPoint (PPTX)
This will export the slides as images. Later editing in PPTX is not possible.
```bash
# Export to PPTX
pnpm export --format pptx

# Or with custom name
pnpm export --format pptx --output my-presentation.pptx
```

**Note:** PPTX export requires playwright. Install it if needed:
```bash
pnpm add -D playwright-chromium
npx playwright install chromium
```

### Export Options

```bash
# Export with notes
pnpm export --with-clicks

# Export dark theme
pnpm export --dark

# Export specific slides (e.g., slides 1-10)
pnpm export --range 1-10
```
</details>