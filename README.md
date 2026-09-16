# Uncle Tetsu Operations - UI Demo

A browser-based, UI-only demo of a possible internal operations platform for Uncle Tetsu. It uses realistic sample data and does **not** connect to a database or save changes.

## Pages

- **Dashboard** - weekly orders, production summary and issues needing attention
- **Store Orders** - store-level batch and packaging orders with delivery dates and status
- **Factory Plan** - consolidated ingredient requirements, supplier-unit rounding and purchase quantities
- **Issue Tickets** - assignments, priority, status, photo placeholders, comments and history
- **Recipes & Batches** - production yield and batch-size reference cards

The "New store order" and "Report an issue" buttons open interactive forms. Search and status filtering work on the Store Orders page. Clicking an issue shows its activity history. Because this is a demo, changes are not persisted.

## Run it

No installation or build step is needed.

### Fastest option

Open `index.html` in Chrome, Edge, Firefox or Safari.

### Recommended local server

From this folder, run:

```bash
python3 -m http.server 8080
```

Then open: <http://localhost:8080>

You can also use VS Code's **Live Server** extension.

## Tech

Plain HTML, CSS and JavaScript. The project is intentionally dependency-free so it is easy to run on any laptop and easy to rebuild later in React or Next.js.
