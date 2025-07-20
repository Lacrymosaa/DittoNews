# DittoNews

**DittoNews** is a fan-made, interactive news page designed to display update logs and headlines using a simple `JSON`-driven structure. It is styled with custom CSS and dynamically loads news entries through JavaScript.

This project serves as an example of how to create a lightweight, modular, and responsive news interface for games, mods, or community projects.

---

## Features

- Dynamically loads news headlines from a `news.json` file.
- Displays news content in a clean central panel.
- Simple left-hand navigation for selecting articles.
- Progress bars and status indicators on the right panel for development tracking.
- Fully static and self-contained (no frameworks required).

---

## How It Works

1. The **left panel** (`#leftWindow`) is populated from `news.json`, generating clickable links for each article.
2. Clicking a headline updates the **middle panel** (`#newsTitle` and `#newsContent`) with the article's title and HTML-formatted content.
3. The **right panel** displays static progress bars for development status and goals.
4. The default content shown on load is the `"home"` entry from the JSON file.

---

## Example `news.json`

```json
[
  {
    "id": "home",
    "title": "Welcome to DittoNews",
    "content": "<p> Welcome !!! </p>"
  },
  {
    "id": "update1",
    "title": "Next Update info",
    "content": "<p>The developer shared a few exciting notes today. Here's what we know so far...</p>"
  }
]

