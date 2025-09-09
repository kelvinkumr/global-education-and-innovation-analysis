# global-education-and-innovation-analysis
Exploring the relationship between economic indicators, innovation, and education.”


## 📊 Global Education and Innovation Analysis Project

### 📌 Project Summary
This project investigates relationships between economic indicators, innovation, and education using data wrangling and analysis. Three key research questions were addressed:

#### 1. Do countries with a higher-than-average GDP per capita have more universities ranked in the top 100 in 2015?
  * Yes. Higher GDP per capita correlates with more top-ranked universities.  
  * Only 4% of top universities came from countries below the average GDP.
  * The US alone accounted for over 50% of the top 100 universities.

#### 2. What subregion produced the most patents in 2014?
  * Northern America (93,685 patents) and Eastern Asia (92,267 patents) lead global innovation.
  * Western Europe also contributed significantly with 66,728 patents.
  * Emerging regions such as Southern Asia and Eastern Europe are growing innovation hubs.

#### 3. Do countries with a higher land area have more universities established in 2012?
  * Larger countries (e.g., the USA) often have more universities, but land area is not the sole factor.
  * Smaller nations like the UK and France also have many universities, showing economic and historical influences are equally important.

#### 🔑 Final Insight
  * Higher GDP per capita is strongly linked to top universities.
  * Patent production is dominated by North America and East Asia.
  * Land area plays a role in university distribution, but other factors are equally significant.

## 📂 Data Wrangling
This project combined datasets from World University Rankings and GDP Among World.

### Datasets Used
* World University Rankings (CSV): [Kaggle Dataset](https://www.kaggle.com/datasets/mylesoneill/world-university-rankings)
* GDP Among World (JSON): [Kaggle Dataset](https://www.kaggle.com/datasets/darknez/gdp-among-world)
* Additional merged dataset prepared via Excel Power Query.

### Key Wrangling Steps
1. Loaded CSV and JSON data into Excel Power Query.
2. Converted and expanded JSON fields into tabular format.
3. Standardised country names (e.g., “United States” → “USA”).
4. Created lookup columns ```(VLOOKUP)``` to merge GDP and university data.
5. Converted GDP values into numeric format for analysis.
6. Built pivot tables and pivot charts to explore correlations.

## 📈 Methods  
  * Excel Power Query for data cleaning and merging.
  * Pivot Tables & Charts for structured analysis.
  * Formulas like ```VLOOKUP``` and ```UNIQUE``` to cross-reference datasets.
  * Filtering & Sorting to isolate relevant years (2012, 2014, 2015).

## 📊 Results at a Glance
  * 🌍 GDP vs Universities: Richer countries dominate global rankings.
  * 💡 Innovation: Patents cluster in North America, East Asia, and Western Europe.
  * 🏫 Land Area vs Universities: Correlation exists, but socio-economic factors are critical.

## 🚀 How to Use This Project
  1. Download the datasets (see links above).
  2. Open in Excel with Power Query enabled.
  3. Follow wrangling steps to reproduce merged dataset.
  4. Generate pivot tables/charts to replicate analysis.

## 📝 Author
Kelvin Kumar
