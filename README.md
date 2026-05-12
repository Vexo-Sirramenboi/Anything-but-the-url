# Template Tools

A lightweight, browser-based utility dashboard for working with text, JSON, HTML, and encoded data.  
Built as a single-file web application with no dependencies, focused on speed, clarity, and a clean dark UI.

---

## Overview

Template Tools combines multiple developer utilities into one interface that runs entirely in the browser.  
No backend, no installs, no frameworks — just open and use.

Everything is handled client-side using JavaScript.

---

## Features

- URL extraction using regex
- Base64 encode / decode
- Text statistics (characters + words)
- JSON validator and formatter
- Live HTML runner (preview in new tab)
- UUID generator
- Word order reverser
- Collapsible sidebar for tool selection
- Cursor-reactive spotlight effect
- Animated grid background
- Copy, clear, and run workflow

---

## How It Works

1. Paste or type input into the text area  
2. Select a tool from the sidebar  
3. Click **Run**  
4. View output instantly  

Each tool processes the same input field but produces different outputs depending on selection.

---

## Tools Breakdown

### URL Extractor

Extracts all URLs from input text using regex.

```js
/https?:\/\/[^\s]+/g
