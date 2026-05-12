# Anything But The URL

A lightweight web tool that extracts all URLs from a block of text instantly.  
Built with plain HTML, CSS, and JavaScript, and runs entirely in the browser.

---

## Live Tool

https://vexo-sirramenboi.github.io/Anything-but-the-url/

---

## Features

- Extracts all `http` and `https` links from text
- Fast and minimal interface
- No installation required
- Fully client-side (no data is sent anywhere)
- Clean dark-themed UI

---

## How It Works

1. Paste or type text into the input field  
2. Click the **Extract** button  
3. All detected URLs are displayed below  
4. Each link is listed on a new line

The tool uses a regular expression to detect URLs inside text.

---

## Regex Used

```js
/https?:\/\/[^\s]+/g
