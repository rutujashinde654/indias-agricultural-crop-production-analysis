# India's Agricultural Crop Production Analysis

A Flask website for exploring India's agricultural crop-production analysis through interactive Tableau dashboards and a Tableau Story.

## Features

- Responsive agriculture-themed analytics interface.
- Interactive Tableau dashboard and story embeds.
- Direct links to open both Tableau Public views.
- Flask serves the page and its stylesheet during local development.

## Project structure

```text
.
├── app.py
├── requirements.txt
├── vercel.json
├── public/
│   └── css/
│       └── style.css
├── static/
│   └── css/
│       └── style.css
└── templates/
    └── index.html
```

`public/css/style.css` mirrors `static/css/style.css` so Vercel can serve the stylesheet from its static asset directory. Keep the two files in sync when changing the site styles. The Vercel rewrite preserves the existing Flask-generated `/static/css/style.css` URL.

## Run locally

1. Create and activate a virtual environment.
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Start Flask:

   ```bash
   python app.py
   ```

4. Open <http://127.0.0.1:5000>.

## Deploy to Vercel

1. Push this project to GitHub.
2. Sign in to [Vercel](https://vercel.com/) and select **Add New → Project**.
3. Import `rutujashinde654/indias-agricultural-crop-production-analysis`.
4. Leave the framework preset and build settings on their detected defaults, then select **Deploy**.

Vercel detects the Flask application in `app.py`, installs Flask from `requirements.txt`, and uses `vercel.json` to serve the stylesheet from `public/`.

## Tableau views

- Dashboard: [Open Tableau Public dashboard](https://public.tableau.com/app/profile/rutuja.shinde1007/viz/tableau_17913568343860/Dashboard2?publish=yes)
- Story: [Open Tableau Public story](https://public.tableau.com/app/profile/rutuja.shinde1007/viz/STORY_17912681662470/Story1)

The dashboard embeds a published Tableau Public visualization; the Flask site does not store Tableau data or credentials.
