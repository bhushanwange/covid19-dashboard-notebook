# COVID-19 Dashboard Notebook

An interactive Jupyter Notebook dashboard built with `pandas`, `matplotlib`, and `seaborn` to visualize COVID-19 case trends, regional and monthly patterns, and top-affected countries[cite: 7].

## Dashboard Highlights
* **Dataset Loading:** Imports the local COVID-19 dataset (`covid19_data.csv`) using `pandas` and formats dates/months[cite: 7].
* **Time-Series Line Chart:** Tracks confirmed cases and deaths over time with clear titles and legends[cite: 7].
* **Region & Month Heatmap:** Compares confirmed case intensity across regions and months[cite: 7].
* **Top 10 Countries Bar Chart:** Ranks the top 10 countries by confirmed cases[cite: 7].
* **Additional Visualizations:** Includes regional horizontal totals and box plot distributions along with Markdown explanations and insights[cite: 7].

## Project Structure

```text
covid19-dashboard-notebook/
├── covid19_data.csv        # Local COVID-19 dataset
├── covid19_dashboard.ipynb # Dashboard notebook with visualizations and notes
├── README.md               # Project documentation
└── .gitignore              # Ignored cache and checkpoint files