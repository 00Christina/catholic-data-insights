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
```

## 📊 Data Sources & Attribution

We are deeply grateful to the open-data projects, archives, and academic repositories that make these visualizations possible:

* **St. Carlo Acutis Eucharistic Miracles Archive:** Miracle locations, historical notes, and media derived from [miracolieucaristici.org](https://www.miracolieucaristici.org/).
* **GCatholic Data Engine:** Global ecclesiastical jurisdictions, historical diocese boundaries, and papal statistics from [GCatholic.org](https://www.gcatholic.org/).
* **CatholicSaints.Info:** Hagiographic data, feast days, and patronage attributes from [CatholicSaints.Info](https://catholicsaints.info/).
* **Wikidata SPARQL Endpoint:** Papal timelines, birthplaces, and schism network nodes via [Wikidata Query Service](https://query.wikidata.org/).

> **Note on Data Usage:** This project is for educational and research visualization purposes only. All underlying intellectual property remains with the original archive maintainers.
---

## Contributing

Contributions are welcome! Whether you're adding new data pipelines, improving map performance, or refining chart aesthetics:

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## License

Distributed under the MIT License. See `LICENSE` for more information.
