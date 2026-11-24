# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

See `README.md` for the project overview and file list.

## Deploy

Hosted on GitHub Pages from `main` at https://leandroz.github.io/mybio/. There is no build step, no bundler, and no `package.json` — edit HTML, commit, push, and GitHub Pages serves it.

The `firebase-debug.log` in the working tree is stale leftover from an abandoned Firebase experiment. Don't commit it, and don't propose Firebase changes unless explicitly asked.

## CSS

Keep all CSS inline in a `<style>` block at the top of each HTML file. Don't extract to external `.css` files — these pages are intentionally single-file.
