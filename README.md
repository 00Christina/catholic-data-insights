# Catholic Data Insights & Visualizations

An open-source, interactive data exploration engine that transforms historical, spatial, and relational Church data into intuitive visual dashboards. This project brings together centuries of ecclesiastical history—from saintly patronages and Eucharistic miracle locations to papal lineages and the complex branching of Christian history.

---

## 📸 Key Dashboards & Features (forthcoming)

### 1. Saint Attributes & Analytics
* **Patronage Heatmaps:** Analyze relationships between saint attributes, feast days, and historical eras.
* **Canonization Timelines:** Visualize time elapsed between death and canonization across papacies.
* **Order Breakdown:** Quantitative distribution across monastic and religious orders (Franciscans, Dominicans, Jesuits, etc.).

### 2. Eucharistic Miracles (St. Carlo Acutis Documentation)
* **Global Interactive Map:** Geospatial pins of 130+ Vatican-approved miracles cataloged by St. Carlo Acutis.
* **Temporal & Regional Analysis:** Histograms tracking miracle occurrences from early antiquity to modern history.
* **Physical Phenomenon Classifier:** Structured taxonomy of scientific and historical evidence recorded.

### 3. Popes Through the Ages
* **Reign Duration Timeline:** Interactive Gantt charts showing pontificates from St. Peter to the present.
* **Geographic Origins:** Dynamic mapping showing the historical shift of papal birthplaces across eras.
* **Regnal Frequency:** Frequency analysis of papal names across centuries.

### 4. The Christian Tree (Denominational Lineage)
* **Interactive Network Graph:** Node-edge graph rendering the historical branching of Christianity (Oriental Orthodoxy, 1054 Great Schism, 1517 Reformation, up through modern denominations).

---

## Repository Architecture

```text
catholic-data-insights/
├── .github/
│   └── workflows/              # Automated data validation workflows
├── data/
│   ├── raw/                    # Raw JSON/CSV scrapes (unmodified source files)
│   └── processed/              # Normalized GeoJSON and parquet data tables
├── scripts/
│   ├── scrapers/               # Python ETL scripts for acquiring datasets
│   └── etl/                    # Geocoding and data transformation pipelines
├── frontend/                   # Interactive Dashboard Application
│   ├── src/                    # UI components, D3 charts, Leaflet maps
│   └── public/
├── docs/                       # Data dictionaries and source attribution
├── LICENSE
└── README.md
