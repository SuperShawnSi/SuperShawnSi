# GitHub Profile Refresh Implementation Plan

> **For Claude:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Refresh the `SuperShawnSi` GitHub profile README into an editorial-style personal landing page that connects software engineering and photography.

**Architecture:** Keep the final deliverable GitHub-native: one profile `README.md` plus lightweight local SVG assets in `assets/`. Use structured Markdown/HTML for layout and pure SVG for the hero banner and showcase card so the profile stays portable and easy to edit.

**Tech Stack:** Markdown, HTML-in-Markdown, SVG

---

### Task 1: Create Visual Assets

**Files:**
- Create: `assets/banner.svg`
- Create: `assets/ppass-card.svg`
- Create: `assets/divider.svg`

**Step 1: Draft the visual system**

Define a restrained palette, serif-forward editorial typography, and a geometric signature mark derived from the photography project branding.

**Step 2: Build the hero banner**

Create a wide SVG banner with:
- a quiet off-white background
- a strong typographic nameplate
- an engineering / photography positioning line
- layered frame motifs inspired by the PP@SS homepage

**Step 3: Build the project showcase card**

Create a supporting SVG card for the featured project section with:
- project title and short narrative
- stack tags
- a simplified system-flow composition

**Step 4: Add a reusable divider**

Create a slim SVG divider that can separate content blocks without visual clutter.

### Task 2: Rewrite the Profile README

**Files:**
- Modify: `README.md`

**Step 1: Replace the placeholder introduction**

Remove the default bullet-point scaffold and replace it with a coherent profile narrative.

**Step 2: Add the new hero section**

Embed the new banner and place a small set of profile links directly below it.

**Step 3: Add the featured build section**

Showcase `PP@SS` as the anchor project with one supporting visual card and concise outcome-focused bullets.

**Step 4: Add personal positioning sections**

Add sections for current focus, engineering interests, and contact links while keeping the page readable and minimal.

### Task 3: Verify Rendering Assumptions

**Files:**
- Verify: `README.md`
- Verify: `assets/banner.svg`
- Verify: `assets/ppass-card.svg`
- Verify: `assets/divider.svg`

**Step 1: Check Markdown structure**

Ensure links, headings, and embedded images use relative paths that GitHub can render.

**Step 2: Check asset references**

Ensure the SVG files are self-contained and do not depend on external fonts, scripts, or stylesheets.

**Step 3: Review for readability**

Confirm the README reads well without custom CSS and that the content remains clear in plain GitHub rendering.
