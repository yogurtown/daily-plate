# Daily Plate V11 — Bugfix

- K preset: 1290 kcal / 55g protein / 155g carbs / 50g fat.
- Red preset: 1650 kcal / 90g protein / 195g carbs / 57g fat.
- Corrected the carbohydrates input selector (`carbTarget` rather than `carbsTarget`). This previously threw a JavaScript error during initialization, preventing all remaining UI including Food Library and food choices from loading.
- One-time preset migration; existing food logs, Food Library records and Others preset stay intact. Future edits to presets remain saved.
- All data remains in browser localStorage.

Before upgrading, export a backup from the working version if possible. Upload `index.html` to your existing GitHub Pages location.

## Version 12
Added the heading “How Much Can I Still Eat?” immediately above the Protein and Carbohydrates cooked-food portion tables in Daily Summary. No change to food calculations, presets, storage keys or food logs.

## V13
- K target: 1200 kcal, 55g protein, 110g carbohydrates, 60g fat.
- Red target: 1900 kcal, 100g protein, 240g carbohydrates, 60g fat.
- One-time preset migration preserves existing food library, logs and Others target.
- Food Log initializes to local calendar date and switches to the new day at midnight (including after tab resumes). Manual selection of older dates is supported until the next rollover.
- Header logo 130px on desktop and 100px on narrow screens.

## V14
K preset: 1,290 kcal, 55g protein, 155g carbs, 50g fat. Red preset unchanged at 1,900 kcal, 100g protein, 240g carbs, 60g fat. One-time migration preserves existing logs, library and other preset.
