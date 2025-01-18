# India-Australia Trade Data Visualization Dashboard

## Project Summary
This project provides a comprehensive, interactive visualization of India-Australia trade data, focusing on export and import values. It is a web-based dashboard that uses Python-based tools for data scraping, cleaning, and visualization.

---

## Tools & Libraries
The following tools and libraries are used:
- **Pandas**: For data manipulation and transformation.
- **Dash**: A web framework for creating the interactive dashboard.
- **Plotly**: To generate interactive plots and graphs.
- **Selenium**: For automated web scraping to extract trade data.
- **WebDriver Manager**: Ensures correct versioning and management of Selenium WebDriver binaries.
- **OpenPyXL**: For reading and writing Excel files.

---

## Data Source
The trade data is sourced from the Ministry of Commerce's Trade Statistics portal:  
[https://tradestat.commerce.gov.in/eidb/default.asp](https://tradestat.commerce.gov.in/eidb/default.asp)

---

## Project Structure

```
project/
├── data/
│   ├── scraped_import_data_2023.xlsx
│   ├── scraped_export_data_2023.xlsx
│   ├── cleaned_import_data.xlsx
│   └── cleaned_export_data.xlsx
├── scripts/
│   ├── Import_scrape_year.py
│   ├── Export_scrape_year.py
│   ├── clean.py
│   └── Dashboard.py
└── README.md
```

---

## Instructions

1. **Install Required Libraries**  
   Run the following command to install all required libraries:
   ```bash
   pip install pandas dash plotly selenium webdriver-manager openpyxl
   ```

2. **Scrape and Clean the Data**  
   Navigate to the `scripts` directory and run the following scripts:
   ```bash
   python Import_scrape_year.py
   python Export_scrape_year.py
   python clean.py
   ```

3. **Start the Dashboard**  
   Run the dashboard script:
   ```bash
   python Dashboard.py
   ```

4. **Access the Dashboard**  
   Open your web browser and go to [http://127.0.0.1:8050](http://127.0.0.1:8050) to view the dashboard.

---
