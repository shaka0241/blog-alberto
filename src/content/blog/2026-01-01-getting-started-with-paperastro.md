---
title: "Getting Started with PaperAstro"
description: "Learn what PaperAstro is, how it works, and how to build a fast, content‑focused Astro site using the PaperCSS aesthetic."
pubDate: "2026-01-01"
heroImage: "../../assets/scrap-placeholder.png"
---

PaperAstro is a lightweight, developer‑friendly starter template for building fast, content‑focused websites with **Astro** and **PaperCSS**. If you want a simple blog or documentation site with a playful, hand‑drawn aesthetic, PaperAstro gives you a clean foundation without the complexity of a full design system.

You can explore the full source code on GitHub:  
https://github.com/fabformhub/paperastro

This guide explains what PaperAstro includes, how the project is structured, and how to start creating your own posts.

## What is PaperAstro?

PaperAstro is a minimal Astro starter designed for developers who want:

- A clean, readable layout  
- A lightweight CSS aesthetic inspired by **PaperCSS**  
- A fast, zero‑JavaScript‑by‑default site  
- A simple content workflow using **Astro Content Collections**  

It’s ideal for:

- Personal blogs  
- Developer notes  
- Documentation sites  
- Minimal landing pages  
- Markdown‑driven content hubs  

Out of the box, PaperAstro includes:

- A sketch‑style UI powered by **PaperCSS**  
- Built‑in support for **Markdown** and **MDX**  
- Automatic **RSS feed** and **sitemap** generation  
- Optimized images using Astro’s image tools  
- Seamless form handling via **Fabform.io**  
- A clear, beginner‑friendly project structure  

## Why developers choose PaperAstro

Many Astro starters are either too minimal or too opinionated. PaperAstro sits in the sweet spot: expressive enough to feel unique, but simple enough to extend without fighting the framework.

Developers often choose PaperAstro because it:

- Loads fast and scores highly on Core Web Vitals  
- Requires almost no configuration  
- Keeps styling lightweight and easy to override  
- Works perfectly for content‑heavy sites  
- Encourages a clean, minimal writing workflow  

## Writing content in PaperAstro

All blog posts live in the `src/content/blog/` directory.  
Each post uses frontmatter to define metadata:

- `title`  
- `description`  
- `pubDate`  
- `heroImage`  

You can write posts in **Markdown** or **MDX**, depending on whether you need components or interactivity.

This structure makes PaperAstro ideal for SEO‑friendly, content‑driven sites.

## Adding hero images

Hero images are stored in `src/assets/`.  
PaperAstro uses Astro’s built‑in image optimization to ensure images are:

- responsive  
- compressed  
- automatically sized  

Just reference the file path in your frontmatter:


## Customizing the layout

PaperAstro is intentionally minimal so you can shape it to your needs.  
To customize the blog layout, explore:

- `src/layouts/BlogLayout.astro`  
- `src/components/PostCard.astro`  
- `src/styles/global.css`  

You can adjust typography, spacing, colors, or even swap out PaperCSS entirely if you want a different aesthetic.

## Next steps

If you're ready to build your first PaperAstro site:

1. Clone the repository  
2. Create your first Markdown or MDX post  
3. Add a hero image  
4. Customize the layout to match your style  

PaperAstro gives you a fast, expressive starting point for any content‑focused project — without the overhead of a full design system.

