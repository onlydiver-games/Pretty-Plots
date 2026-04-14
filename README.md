# Pretty Plots

**Free, browser-based scientific data visualization tool.**

(https://onlydiver-games.github.io/Pretty-Plots/)
--
## Features

**Plot types**
- Scatter plots — color/size by data column, per-category trendlines
- Line plots — fill, dash styles, per-category trendlines
- Bar charts — vertical/horizontal, 5 aggregation functions
- Stacked & grouped bar charts
- Box plots — with outliers and mean marker
- Contour plots — auto-fitted regression surface, labeled contours
- 3D surface plots — interactive rotation/zoom, surface contour lines, wireframe

**Data**
- Upload CSV or Excel (`.csv`, `.xlsx`, `.xls`)
- Hide/show individual rows from analysis without deleting them
- Categorical columns automatically detected and used for color grouping

**Regression (Contour & 3D)**
- Automatic least-squares fit: `y = A·x₁ + B·x₂ + C·x₁x₂ + D·x₁² + E·x₂²`
- Toggle 2nd-order terms and interaction term on/off
- Displays fitted formula, R², and RMSE

**Styling**
- 9 style presets: Dark Grid, White Grid, Dark, White, Ticks, Poster, Talk, Paper, Notebook
- 8 color themes for categorical data (Office, Vivid, Pastel, Colorblind Safe, etc.)
- 19 colormaps with gradient preview dropdown
- Colormap min / midpoint / max override — set a tipping point to a specific color
- Per-plot font family, title size, axis label size, tick size, legend size
- All plots export as PNG

---

## Usage

No installation, no server, no dependencies to install. Just open the HTML file.

**Option 1 — Use the live site**
Visit the GitHub Pages URL above.

**Option 2 — Run locally**
```bash
git clone https://github.com/your-username/pretty-plots.git
cd pretty-plots
open pretty_plots.html   # macOS
# or just double-click pretty_plots.html in your file explorer
```

**Option 3 — Download the file**
Download `pretty_plots.html` and open it in any modern browser. No internet connection required after the initial load (Google Fonts will be missing offline, but everything else works).

---

## Deploying to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`
4. Save — your site will be live at `https://your-username.github.io/pretty-plots/`

That's it. GitHub Pages serves the `index.html` which redirects to `pretty_plots.html`.

---



## License

MIT — use it, fork it, build on it.
