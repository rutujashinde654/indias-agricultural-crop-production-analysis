# 🇮🇳 India's Agricultural Crop Production Analysis

## 📌 Project Overview

**India's Agricultural Crop Production Analysis** is a data analytics and visualization project that explores agricultural crop production patterns across India using **Tableau**.

The project transforms agricultural data into interactive **Tableau Dashboards and Stories** and integrates them into a **Flask-based web application**. This allows users to explore agricultural insights through an accessible and interactive web interface.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze India's agricultural crop production data.
* Identify production patterns and trends.
* Compare crop production across different regions and years.
* Present important insights using interactive Tableau visualizations.
* Create an interactive Tableau Dashboard and Story.
* Integrate Tableau visualizations into a Flask web application.
* Deploy the web application for public access.

---

## 🗂️ Project Workflow

```text
Agricultural Dataset
        ↓
Data Collection
        ↓
Data Cleaning & Preparation
        ↓
Tableau Data Analysis
        ↓
Tableau Visualizations
        ↓
Tableau Dashboard
        ↓
Tableau Story
        ↓
Flask Web Integration
        ↓
GitHub
        ↓
Vercel Deployment
        ↓
Live Web Application
```

---

## 📊 Data Collection & Extraction

The agricultural dataset is used to analyze crop production across India.

The data contains agricultural information that can be explored through dimensions such as:

* State/Region
* Crop
* Year
* Production
* Agricultural measurements available in the dataset

The dataset was imported and prepared for analysis before creating the Tableau visualizations.

> **Note:** The exact number of records and columns depends on the dataset used for the project.

---

## 🧹 Data Preparation

Before visualization, the dataset was prepared for analysis.

The preparation process included:

1. Importing the agricultural dataset.
2. Checking the dataset structure.
3. Identifying missing or incomplete values.
4. Checking duplicate records.
5. Verifying column data types.
6. Preparing fields required for visualization.
7. Organizing the data for Tableau analysis.

The cleaned/prepared data was then used to build the Tableau Dashboard and Story.

---

# 📈 Data Visualization

Tableau was used to convert the agricultural dataset into interactive visualizations.

The visualizations help users understand:

* Crop production patterns.
* Regional differences.
* Production trends.
* Crop-wise comparisons.
* Agricultural performance across different periods.

Interactive filters and visual elements allow users to explore the data according to their requirements.

---

# 📊 Tableau Dashboard

The Tableau Dashboard provides an interactive overview of India's agricultural crop production.

### Dashboard Features

* Interactive charts
* Crop-wise analysis
* Region/state-wise analysis
* Production comparisons
* Filters
* Data-driven insights

### 🔗 Tableau Public Dashboard

[Open Tableau Public Dashboard](https://public.tableau.com/app/profile/rutuja.shinde1007/viz/tableau_17913568343860/Dashboard2?publish=yes)

---

# 📖 Tableau Story

The Tableau Story presents the analysis in a structured sequence.

It helps users understand the agricultural data step-by-step and identify important trends and patterns.

### 🔗 Tableau Public Story

[Open Tableau Public Story](https://public.tableau.com/app/profile/rutuja.shinde1007/viz/STORY_17912681662470/Story1)

---

# 🌐 Web Integration

The Tableau Dashboard and Story are integrated into a Flask web application.

The web application provides a simple interface through which users can access the Tableau visualizations directly from a browser.

### Integration Architecture

```text
User
 │
 ▼
Flask Web Application
 │
 ├── HTML
 ├── CSS
 │
 ▼
Tableau Public
 │
 ├── Interactive Dashboard
 │
 └── Interactive Story
```

The Tableau visualizations are embedded into the Flask website using web embedding.

---

# 🖥️ Flask Application

The Flask application acts as the web layer of the project.

### Flask Responsibilities

* Runs the web application.
* Serves the HTML page.
* Serves CSS/static files.
* Provides the home route.
* Displays the embedded Tableau visualizations.

The main Flask application is contained in:

```text
app.py
```

---

# 🛠️ Technology Stack

| Technology     | Purpose                      |
| -------------- | ---------------------------- |
| Python         | Backend programming          |
| Flask          | Web application framework    |
| HTML           | Webpage structure            |
| CSS            | Website styling              |
| Tableau        | Data visualization           |
| Tableau Public | Dashboard & Story publishing |
| GitHub         | Source code management       |
| Vercel         | Web deployment               |

---

# 📁 Project Structure

```text
indias-agricultural-crop-production-analysis/
│
├── app.py
├── requirements.txt
├── vercel.json
├── README.md
│
├── public/
│   └── css/
│       └── style.css
│
├── static/
│   └── css/
│       └── style.css
│
└── templates/
    └── index.html
```

### Important

The Flask application uses the `static` directory for CSS and other static resources.

The `public` directory is also maintained for Vercel static asset handling.

---

# 🧪 Performance Testing

The web application was tested for:

* Flask application loading.
* Tableau Dashboard loading.
* Tableau Story loading.
* Interactive visualization functionality.
* Navigation.
* CSS loading.
* Responsive webpage behavior.
* Tableau Public accessibility.
* Deployment functionality.

---

# 🚀 Run the Project Locally

## 1. Clone the repository

```bash
git clone https://github.com/rutujashinde654/indias-agricultural-crop-production-analysis.git
```

## 2. Open the project

```bash
cd indias-agricultural-crop-production-analysis
```

## 3. Create a virtual environment

### Windows

```bash
python -m venv venv
```

Activate it:

```bash
venv\Scripts\activate
```

## 4. Install dependencies

```bash
pip install -r requirements.txt
```

## 5. Run Flask

```bash
python app.py
```

## 6. Open the application

Open:

```text
http://127.0.0.1:5000
```

---

# ☁️ Deployment

The Flask application can be deployed using **Vercel**.

### Deployment Process

```text
GitHub Repository
       ↓
Vercel
       ↓
Import Repository
       ↓
Deploy
       ↓
Live Web Application
```

### Deployment Steps

1. Push the project to GitHub.
2. Open Vercel.
3. Select **Add New → Project**.
4. Import this GitHub repository.
5. Allow Vercel to detect the project configuration.
6. Deploy the application.
7. Open the generated deployment URL.

---

# 🔗 Project Links

### 💻 GitHub Repository

[View Source Code](https://github.com/rutujashinde654/indias-agricultural-crop-production-analysis)

### 📊 Tableau Dashboard

[Open Dashboard](https://public.tableau.com/app/profile/rutuja.shinde1007/viz/tableau_17913568343860/Dashboard2?publish=yes)

### 📖 Tableau Story

[Open Story](https://public.tableau.com/app/profile/rutuja.shinde1007/viz/STORY_17912681662470/Story1)

### 🌐 Live Demo

**Add your Vercel deployment URL here after deployment.**

```text
https://your-project-name.vercel.app
```

---

# 📸 Project Demonstration

The project demonstration should cover:

1. Opening the web application.
2. Viewing the Tableau Dashboard.
3. Interacting with dashboard filters.
4. Exploring the Tableau Story.
5. Navigating between dashboard/story sections.
6. Demonstrating responsive behavior.
7. Showing the GitHub repository.
8. Showing the deployed application.

---

# 💡 Key Outcomes

The project demonstrates how agricultural data can be transformed into meaningful visual insights using Tableau and then delivered through a web application.

The integration of **Tableau + Flask + GitHub + Vercel** provides a complete workflow from data analysis to web-based data storytelling.

---

# 🏁 Conclusion

**India's Agricultural Crop Production Analysis** demonstrates the complete process of collecting, preparing, analyzing, visualizing, and presenting agricultural data.

Tableau provides the interactive analytical layer, while Flask provides the web application layer. The project makes agricultural insights more accessible through an interactive web interface containing both a Tableau Dashboard and Story.

---

## 👩‍💻 Author

**Rutuja Shinde**

Data Analytics & AI/DS Student

---

⭐ If you find this project useful, consider giving the repository a star!
