# SuperStore Sales — Data Modeling & BI Dashboard

> Data engineering and analytics project: import a real-world retail dataset, design a relational schema, model it in **MoonModeler / MySQL Workbench**, and visualize the insights in **Power BI**.

## What this project covers

- **Data modeling** — designing a normalized relational schema for a retail business (Customers · Orders · Products)
- **Schema documentation** — `.mwb` (MySQL Workbench) and `.dmm` (MoonModeler) diagrams
- **Data ingestion** — JSON datasets parsed and loaded into the database
- **Reporting** — interactive Power BI dashboard with KPIs and breakdowns

## Repository contents

```
├── JSON_Customers.txt      # Customers dataset (JSON)
├── JSON_Orders.txt         # Orders dataset (JSON)
├── JSON_Products.txt       # Products dataset (JSON)
├── MoonModeler.dmm         # MoonModeler schema diagram
├── SQL.mwb                 # MySQL Workbench data model
└── dashboard_powerbi.pbix  # Power BI dashboard
```

## Tech stack

- **Database modeling:** MySQL Workbench, MoonModeler
- **Data format:** JSON
- **Query language:** SQL
- **Visualization:** Microsoft Power BI

## How to explore

1. **View the data model:** open `SQL.mwb` in MySQL Workbench (or `MoonModeler.dmm` in MoonModeler).
2. **Inspect the data:** the three `JSON_*.txt` files contain the raw records.
3. **Open the dashboard:** open `dashboard_powerbi.pbix` in Power BI Desktop to see the analyses and KPIs.

## What I learned

- Translating a business domain (retail) into a normalized relational schema
- Designing entity relationships that are both correct and queryable
- Building reports that surface useful business questions, not just charts
- Working across the full data path: JSON → SQL → BI

## Author

**Jakub Antala** — Applied Informatics, UKF Nitra
📧 jakub.antala10@gmail.com

---

<sub>🇸🇰 <em>Dátový projekt — návrh relačnej schémy pre retailové dáta (zákazníci, objednávky, produkty), import z JSON a vizualizácia v Power BI dashboarde. Obsahuje SQL model aj interaktívny report.</em></sub>
