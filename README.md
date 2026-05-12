# 🍕 NitroStack Pizza Shop Finder

A high-performance interactive template showcasing discovery with maps, lists, and detailed views. This template demonstrates the **NitroStack Widget SDK** for building beautiful, tool-driven visual experiences.

## ✨ Features

- **Mapbox Integration** — Interactive maps with custom markers.
- **Real-time State** — Shared state between server and widgets.
- **Responsive Layouts** — Auto-adapting heights and display modes (Inline, PiP, Fullscreen).
- **Interactive UI** — Sorting, filtering, and favorites persistence.

---

## 🚀 Quick Start

### 1. Initialize Your Project

```bash
npx nitrostack init my-pizza-app --template typescript-pizzaz
cd my-pizza-app
```

### 2. Install Dependencies

```bash
npm run install:all
```

### 3. Step Up NitroStudio

NitroStudio provides the best experience for visual testing of widgets and maps.

![NitroStudio](../../../../assets/gif/nitrostudio-main.gif)

1. **Download NitroStudio**: [nitrostack.ai/studio](https://nitrostack.ai/studio)
2. **Open Project**: Launch NitroStudio and select your project folder.
3. **View Maps**: Use the chat or visual tools to explore your pizza shops.

---

## ⚙️ Configuration

### Mapbox (Optional)

To enable the interactive map, add your Mapbox token:

1. Get a free token at [mapbox.com](https://www.mapbox.com/).
2. Create `src/widgets/.env` and add:
   ```env
   NEXT_PUBLIC_MAPBOX_TOKEN=pk.your_token_here
   ```

---

## 🛠️ Commands

```bash
# Start dev server with Studio integration
npm run dev

# Build for production
npm run build

# Manage widgets directly
npm run widget <command>
```

## 📁 Structure

- `src/modules/pizzaz/` — Core logic and pizza shop data.
- `src/widgets/app/pizza-map/` — Next.js Map widget.
- `src/widgets/app/pizza-list/` — Filterable shop list.
- `src/widgets/app/pizza-shop/` — Detail view with actions.

---
**Official Resources**
- [Website](https://nitrostack.ai)
- [Docs](https://docs.nitrostack.ai)
- [Download Studio](https://nitrostack.ai/studio)
# pizza
# pizza
