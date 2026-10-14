# Daily Plate V11 — Bugfix

- K preset: 1290 kcal / 55g protein / 155g carbs / 50g fat.
- Red preset: 1650 kcal / 90g protein / 195g carbs / 57g fat.
- Corrected the carbohydrates input selector (`carbTarget` rather than `carbsTarget`). This previously threw a JavaScript error during initialization, preventing all remaining UI including Food Library and food choices from loading.
- One-time preset migration; existing food logs, Food Library records and Others preset stay intact. Future edits to presets remain saved.
- All data remains in browser localStorage.

Before upgrading, export a backup from the working version if possible. Upload `index.html` to your existing GitHub Pages location.
