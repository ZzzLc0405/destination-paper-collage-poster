<div align="center">

# Destination Paper Collage Poster

### A destination-driven paper-cut collage poster skill

Create travel posters that share one recognizable visual language **without repeating one fixed layout**.

[English](README.md) · [简体中文](README.zh-CN.md) · [Skill](SKILL.md) · [License](LICENSE.md)

</div>

---

## Gallery

> Replace the six placeholder images in `examples/` with your own selected posters.  
> Keep the filenames unchanged and this 3 × 2 gallery will update automatically.

<table>
  <tr>
    <td width="33.33%"><img src="examples/poster-01.png" alt="Poster 01"></td>
    <td width="33.33%"><img src="examples/poster-02.png" alt="Poster 02"></td>
    <td width="33.33%"><img src="examples/poster-03.png" alt="Poster 03"></td>
  </tr>
  <tr>
    <td width="33.33%"><img src="examples/poster-04.png" alt="Poster 04"></td>
    <td width="33.33%"><img src="examples/poster-05.png" alt="Poster 05"></td>
    <td width="33.33%"><img src="examples/poster-06.png" alt="Poster 06"></td>
  </tr>
</table>

---

## What this skill does

`Destination Paper Collage Poster` is a visual-generation skill for creating city and destination posters in a layered paper-cut collage style.

Instead of treating every place as a landmark swap inside the same template, the skill first derives a destination-specific visual system from its:

- spatial character
- architecture
- cultural identity
- natural environment
- mobility
- materials
- emotional tone

It then decides the **hero element, composition, title role, palette, foreground, background, supporting motifs, and density** for that destination.

The goal is simple:

> **The same designer should be recognizable. The same template should not.**

---

## Core characteristics

- Layered paper-cut collage with photographic and illustrated elements
- Torn-paper edges, subtle paper depth, soft shadows, controlled grain
- Destination-specific composition rather than a fixed poster template
- One clear hero element or visual relationship
- Flexible title position, scale, direction, and bilingual hierarchy
- Fresh color separation instead of automatic yellowed or vintage grading
- Strong anti-template and reference-drift rules
- Designed for vertical travel posters by default, approximately 5:7

---

## Why it is different

Many travel-poster prompts eventually converge on the same structure: a large title block, several landmarks, a road, a vehicle, flowers, birds, stamps, or other recurring decorations.

This skill explicitly separates **style consistency** from **layout consistency**.

It keeps the paper-collage craftsmanship stable while allowing each destination to generate its own visual rhythm.

---

## Usage

1. Download or copy [`SKILL.md`](SKILL.md).
2. Add it to a tool or model that supports reusable skills / system instructions.
3. Provide a destination and ask for a poster.
4. Add optional constraints only when needed, such as:
   - aspect ratio
   - required landmark
   - mood
   - palette
   - title text
   - orientation
5. Let the skill determine the composition instead of manually forcing one layout.

A minimal request can simply be:

```text
Create a paper-collage travel poster for [destination] using this skill.
```

---

## Design logic

The skill follows this internal flow:

```text
Destination
    ↓
Destination Visual DNA
    ↓
Hero Element
    ↓
Composition Engine
    ↓
Title Composition Engine
    ↓
Foreground / Background / Supporting Motifs
    ↓
Destination-Specific Color System
    ↓
Paper-Collage Construction
    ↓
Anti-Template Check
    ↓
Final Poster
```

---

## Repository structure

```text
destination-paper-collage-poster/
├── SKILL.md
├── README.md
├── README.zh-CN.md
├── LICENSE.md
├── COMMERCIAL-LICENSE.md
└── examples/
    ├── README.md
    ├── poster-01.jpg
    ├── poster-02.jpg
    ├── poster-03.jpg
    ├── poster-04.jpg
    ├── poster-05.jpg
    └── poster-06.jpg
```

---

## Replacing the gallery images

Choose six posters that best represent the range of the skill.

Recommended selection criteria:

- visibly different city structures
- different title placements
- different dominant palettes
- different hero elements
- no repeated composition skeleton
- clear paper-collage craftsmanship

Export them as JPG files and replace:

```text
examples/poster-01.jpg
examples/poster-02.jpg
examples/poster-03.jpg
examples/poster-04.jpg
examples/poster-05.jpg
examples/poster-06.jpg
```

A vertical ratio close to **5:7** is recommended for visual consistency in the gallery.

---

## License & attribution

Copyright © 2026 **AMZhang**. All rights reserved.

This repository is **not released for unrestricted commercial use**.

### Non-commercial use

Personal, educational, research, experimental, and other non-commercial use is permitted provided that clear attribution is given.

For public online use, include a credit such as:

```text
Created with Destination Paper Collage Poster Skill by AMZhang.
Source: [link to this GitHub repository]
```

### Commercial use

**Commercial use requires prior written authorization from the copyright holder.**

Commercial use includes, but is not limited to:

- selling posters, prints, digital downloads, templates, or derivative products
- paid client work
- commercial advertising or brand campaigns
- monetized commercial content
- integrating the skill or a derivative version into a paid product, service, workflow, or platform
- commercial distribution of outputs materially generated using this skill
- resale, relicensing, sublicensing, or paid redistribution of the skill or adapted versions

See [`LICENSE.md`](LICENSE.md) and [`COMMERCIAL-LICENSE.md`](COMMERCIAL-LICENSE.md) for details.

> Rights in AI-generated outputs may also be affected by the terms of the model or platform used to generate them and by applicable law.

---

## Attribution

If you publish work made with this skill for non-commercial purposes, please credit the project and link back to the repository.

Suggested format:

```text
Destination Paper Collage Poster Skill — AMZhang
```

---

## Commercial licensing

For commercial licensing, please contact the repository owner through the contact method provided on the GitHub profile or open a licensing inquiry in the repository.

Commercial licenses may be negotiated by:

- use case
- duration
- territory
- exclusivity
- distribution scale
- output type

---

## Notes

This project provides a reusable creative-generation system. Results will still depend on the capabilities, image model, reference handling, and text-rendering quality of the platform used.

---

<div align="center">

**Same visual language. Different city personality.**

</div>
