# Slidev Presentation Template

A minimal [Slidev](https://sli.dev) template for technical presentations.

## Quick Start

```bash
# Install dependencies
pnpm install

# Start development server
pnpm dev

# Export to PDF
pnpm export

# Export to PowerPoint
pnpm export --format pptx
```

## Structure

- `slides.md` – All slide content (edit this)
- `public/images/` – Presentation images
- `public/logos/` – Logo files for title slide
- `components/` – Custom Vue components

## Customisation

- Change the accent colour by editing the color in `<style>` blocks (each slide has one)
- Add or remove logo `<img>` tags on the title slide
- Use `v-clicks` to reveal bullet points incrementally
- Use `layout: two-cols` with `::right::` for side-by-side content
- LaTeX math works inline (`$...$`) and as blocks (`$$...$$`)
- Add slide numbers with: `{{$slidev.nav.current}} / {{$slidev.nav.total}}`

**Note:** Slidev requires style blocks on each slide for consistent heading styles.

See the [Slidev docs](https://sli.dev) for all available layouts and features.
