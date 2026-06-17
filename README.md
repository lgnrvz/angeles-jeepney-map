# Angeles City Jeepney Route Map

Interactive, color-coded map of all jeepney routes in Angeles City, Pampanga. Single-file HTML — no build step, no dependencies, no server required.

🌐 **Live site:** [lgnrvz.github.io/angeles-jeepney-map](https://lgnrvz.github.io/angeles-jeepney-map)

## Routes

| # | Route | Color |
|---|-------|-------|
| 1 | Capaya - Angeles | 🟣 Pink/Magenta |
| 2 | Sapangbato - Angeles | 🔴 Red |
| 3 | Carmenville - Angeles | 🟠 Orange |
| 4 | Pampang - SM Telabastagan | 🟡 Yellow |
| 5 | Marisol - Pampang | 🟢 Green |
| 6 | Pandan - Angeles | 🔵 Blue |
| 7 | Checkpoint - Holy Angel University | 🟣 Purple |
| 8 | Checkpoint - HAU - Balibago | ⚫ Dark Gray |
| 9 | Checkpoint - Hensonville | ⚪ Light Gray |
| 10 | Friendship Highway | 🟤 Tan/Beige |

## Features

- **Interactive map** — pan, zoom, tap any route for details
- **Color-coded** — each route line matches the real jeepney color
- **Toggle routes** — show/hide individual routes via the legend
- **Dark theme** — easy on the eyes, works day and night
- **Mobile-friendly** — designed for commuters on the go
- **Offline tiles** — map tiles are cached after first load
- **Zero dependencies** — just open `index.html`

## Data

Route data sourced from the community-driven [sakay_ph](https://github.com/lucifuge2003/sakay_ph) project. Each route includes:
- Polyline coordinates (GPS path)
- Starting point
- Popular drop-off points / landmarks

## Contributing

Routes change, new jeepneys get added, colors sometimes shift. If you spot an error or missing route:

1. Fork this repo
2. Edit the `ROUTES` array in `index.html`
3. Submit a PR with your source

## License

Data compiled for public service. Use it, share it, improve it.
