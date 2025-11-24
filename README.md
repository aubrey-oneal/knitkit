# knitkit
A browser-based tool for designing composable, grid-based knitting motifs and assembling them into patterns — a design system for knitters.

## Overview
**knitkit** helps knitters (and knit-curious designers) create composable colorwork motifs and combine them into patterns. Every motif is stored in a structured format, making it easy to transform, remix, and build a searchable library over time.

## Key Terms
- **Motif** — A small design element (e.g., Fair Isle “X” or “O”, a heart, a geometric shape) that can appear alone or inside a repeating pattern of motifs.
- **Pattern** — Any arrangement of one or more motifs. For example, alternating motifs across a sweater yoke, or a repeating band on mittens.
- **Knit Chart** — A visual instruction system for knitters. Charts are typically read *bottom to top* and *right to left*. A chart may show a single motif repeated many times to form a full design.
- **Motif Metadata** — Stored as an array in `.json`, making motifs easy to scale, reflect, rotate, or repeat.

---

## Motif Maker (in progress)
The **Motif Maker** is the drawing tool for creating new motifs.

- Click on the grid to toggle stitches between **main color (MC)** and **contrast color (CC)**.
- Saving a motif writes it to a `.json` file as an array representation of the design.
- Because motifs are stored as arrays, they can be transformed mathematically — scaled up, reflected, rotated, tiled, etc.
- Each motif also includes metadata (title, tags, category, author, etc.) to support indexing and search in future library features.

---

## Pattern Maker (in progress)
The **Pattern Maker** is where motifs are combined, repeated, or scaled to create designs.

- Combine motifs into rows, bands, or complex arrangements.
- Adjust spacing, repetition, scale, and alignment.
- Perfect for planning circular yokes, socks, mittens, or other stranded-colorwork projects.
- Because motifs are array-based, modifying proportions and repeating elements is possible.

**Future possibilities:**
- Auto-generating knit charts in various sizes  
- Previewing patterns on garment templates  
- Exporting instructions 

---

## Motif Library (future feature)
A searchable **Motif Library** will allow users to browse hundreds of motifs by:

- Name or keyword  
- Shape or geometry  
- Craft tradition or historical category  
- Metadata such as licensing, tags, or ratings  

This will eventually support saving favorites, remixing community motifs, and building organized collections.

---
