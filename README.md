# 🎿 Alberto Tomba – World Cup Results Scraper

A Python web scraper that extracts Alberto Tomba's Alpine skiing World Cup results from Wikipedia and structures them into a clean, exportable dataset.

---

## 📋 Description

This project scrapes the [Alberto Tomba Wikipedia page](https://en.wikipedia.org/wiki/Alberto_Tomba), locates the *World Cup Results* section, and parses the data table into a **pandas DataFrame**. Results can be exported to an Excel file (`.xlsx`) for further analysis.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab

### Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/alberto-tomba-scraper.git
cd alberto-tomba-scraper
pip install requests beautifulsoup4 pandas openpyxl lxml
```

Or, from inside the Jupyter notebook:

```python
%pip install requests beautifulsoup4 pandas openpyxl lxml selenium
```

---

## 📦 Dependencies

| Library | Purpose |
|---|---|
| `requests` | Fetching the Wikipedia page |
| `beautifulsoup4` | Parsing HTML content |
| `lxml` | HTML parser backend |
| `pandas` | Structuring data into a DataFrame |
| `openpyxl` | Exporting data to Excel |

---

## 💻 Usage

1. Open `alberto_tomba.ipynb` in Jupyter Notebook or JupyterLab
2. Run all cells
3. The World Cup results table will be printed as a DataFrame
4. To export to Excel, uncomment the last line:

```python
df.to_excel('alberto_tomba_world_cup_results.xlsx', index=False)
```

---

## 📁 Project Structure

```
alberto-tomba-scraper/
│
├── alberto_tomba.ipynb        # Main Jupyter notebook
├── alberto_tomba_world_cup_results.xlsx  # Output file (generated)
└── README.md
```

---

## 📄 License

This project is for educational purposes only. Data sourced from [Wikipedia](https://www.wikipedia.org/) under the [Creative Commons Attribution-ShareAlike License](https://creativecommons.org/licenses/by-sa/4.0/).
