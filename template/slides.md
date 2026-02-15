---
theme: default
class: text-left
transition: fade-out
# Drag positions for logos on the title slide (edit by double-clicking in dev mode)
dragPos:
  KU: 13,13,159,57
  EU: 188,12,203,52
  IceCube: 815,9,57,66
---

# Presentation Title

Subtitle or brief description

**Date:** DD Month YYYY

**Presenter:** Your Name

<!-- Example: draggable logos on the title slide. Place your own in public/logos/ -->
<img v-drag="'KU'" src="./logos/ku_logo.png"/>
<img v-drag="'EU'" src="./logos/EU.png"/>
<img v-drag="'IceCube'" src="./logos/IceCube_vertical.png"/>

<!-- Global styles – change the accent colour here to retheme the whole deck -->
<style>
h1 {font-weight: 900;
  color: #8B0000;}
</style>

---
transition: fade-out
---

# Agenda

- Topic 1
- Topic 2
- Topic 3

<style>
h1 {
  font-weight: 900;
  color: #8B0000;
}
</style>

---
transition: fade-out
---

# Key Points

<v-clicks>

- First point revealed on click
- Second point revealed on click
- Third point revealed on click

</v-clicks>

<!--
v-clicks wraps each child in a click animation.
See https://sli.dev/guide/animations#click-animation
-->

<style>
h1 {
  font-weight: 900;
  color: #8B0000;
}
</style>

---
layout: two-cols
transition: fade-out
---

# Two Columns

Left column content

- Item A
- Item B
- Item C

::right::

Right column content

- Item X
- Item Y
- Item Z

<style>
h1 {
  font-weight: 900;
  color: #8B0000;
}
</style>

---
transition: fade-out
---

# Image Slide

<div class="flex justify-center mt-8">
  <img src="./images/your-image.png" class="max-h-80 rounded shadow" />
</div>

<style>
h1 {
  font-weight: 900;
  color: #8B0000;
}
</style>

---
transition: fade-out
---

# Three Column Cards

<!-- Three styled cards – good for phases, pillars, or comparisons -->
<div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 1.5rem; margin-top: 3rem;">
  <div style="background: linear-gradient(135deg, #fff5f5 0%, #ffe8e8 100%); border: 2px solid #8B0000; border-radius: 12px; padding: 1.5rem; box-shadow: 0 4px 16px rgba(139,0,0,0.12);">
    <h3 style="color: #8B0000; margin-bottom: 1rem;">1. First</h3>
    <p style="font-size: 0.9em;">Description of the first item or phase</p>
  </div>
  <div style="background: linear-gradient(135deg, #f0f9ff 0%, #e0f2fe 100%); border: 2px solid #0369a1; border-radius: 12px; padding: 1.5rem; box-shadow: 0 4px 16px rgba(3,105,161,0.12);">
    <h3 style="color: #0369a1; margin-bottom: 1rem;">2. Second</h3>
    <p style="font-size: 0.9em;">Description of the second item or phase</p>
  </div>
  <div style="background: linear-gradient(135deg, #f0fdf4 0%, #dcfce7 100%); border: 2px solid #15803d; border-radius: 12px; padding: 1.5rem; box-shadow: 0 4px 16px rgba(21,128,61,0.12);">
    <h3 style="color: #15803d; margin-bottom: 1rem;">3. Third</h3>
    <p style="font-size: 0.9em;">Description of the third item or phase</p>
  </div>
</div>

<style>
h1 {
  font-weight: 900;
  color: #8B0000;
}
</style>

---
transition: fade-out
---

# Highlights

<!-- Stacked gradient boxes – good for outcomes, summaries, or key takeaways -->
<div style="display: flex; flex-direction: column; gap: 1.2rem; margin-top: 2rem;">

<div style="background: linear-gradient(90deg, #fff5f5 0%, #f8f9fa 100%); border: 2px solid #8B0000; border-radius: 12px; box-shadow: 0 4px 16px rgba(139,0,0,0.08); padding: 1.2rem;">
  <span style="font-size: 1.05em; font-weight: bold; color: #8B0000;">Highlight One</span>
  <div class="mt-1">Description of the first highlight or outcome</div>
</div>

<div style="background: linear-gradient(90deg, #fff5f5 0%, #f8f9fa 100%); border: 2px solid #8B0000; border-radius: 12px; box-shadow: 0 4px 16px rgba(139,0,0,0.08); padding: 1.2rem;">
  <span style="font-size: 1.05em; font-weight: bold; color: #8B0000;">Highlight Two</span>
  <div class="mt-1">Description of the second highlight or outcome</div>
</div>

<div style="background: linear-gradient(90deg, #fff5f5 0%, #f8f9fa 100%); border: 2px solid #8B0000; border-radius: 12px; box-shadow: 0 4px 16px rgba(139,0,0,0.08); padding: 1.2rem;">
  <span style="font-size: 1.05em; font-weight: bold; color: #8B0000;">Highlight Three</span>
  <div class="mt-1">Description of the third highlight or outcome</div>
</div>

</div>

<style>
h1 {
  font-weight: 900;
  color: #8B0000;
}
</style>

---
transition: fade-out
---

# Math & Code

Inline math: $E = mc^2$

$$
\int_{-\infty}^{\infty} e^{-x^2}\, dx = \sqrt{\pi}
$$

```python
# Code blocks with syntax highlighting
def hello(name: str) -> str:
    return f"Hello, {name}!"
```

<style>
h1 {
  font-weight: 900;
  color: #8B0000;
}
</style>

---
layout: center
class: text-center
transition: fade-out
---

# Thank You

Questions?

<div class="mt-4 text-sm opacity-70">

Your Name · Your Institution · DD Month YYYY

</div>

<style>
h1 {
  font-weight: 900;
  color: #8B0000;
}
</style>
