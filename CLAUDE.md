# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Plain HTML/CSS static site hosted on GitHub Pages at `DDU4251.github.io`. No build system, no framework, no package manager.

## Running the Site

No build step required. To serve locally:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Repository Structure

- `Index.html` — Landing page ("Hello, I'm Johnny")
- `main.html` — Employee data table demo with inline CSS
- `*.L5K` — Allen-Bradley Studio 5000 PLC ladder logic files (version-controlled here, unrelated to the website)

## Git Workflow

The project is used to practice Git flow. The main branch is `main`; active work happens on `my-branch` (tracked against `origin/my-branch`).
