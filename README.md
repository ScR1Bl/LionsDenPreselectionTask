---

# 🏠 Real Estate Price Prediction - LionsDenPreselectionTask  

**Team Equilibrium** | *Apache 2.0 License*  

---

## 📂 Repository Structure  
```
LionsDenPreselectionTask/  
├── main/                          # Main branch  
│  
├── Data/                          # Raw and processed datasets  
│   ├── all_data.csv               # Combined dataset  
│   ├── data_final.csv             # Processed dataset for modeling  
│   ├── otodom_apartment_offers.csv  
│   ├── otodom_house_offers.csv  
│   ├── otodom_studio_offers.csv  
│   ├── otodom_offers_coordinates.csv  # Geocoded property data  
│   ├── average_salary.csv         # Economic indicators  
│   ├── gradual_unemployment_rate.csv  
│   ├── inflation.xlsx  
│   └── population.csv  
│  
├── Notebooks/                     # Jupyter notebooks  
│   ├── Coordinates.ipynb          # Geocoding script  
│   ├── WebScraping_apartments.ipynb  
│   ├── WebScraping_house.ipynb  
│   ├── WebScraping_studio.ipynb  
│   └── real-estate_prediction.ipynb  # Main ML modeling  
│  
├── LICENSE  
└── README.md  
```  

---

## 🛠️ Project Workflow  
1. **Data Collection**  
   - Scraped property listings (apartments, houses, studios) from Otodom (`.ipynb` files).  
   - Collected economic data (salary, unemployment, inflation, population).  

2. **Geocoding**  
   - Converted addresses to coordinates (`Coordinates.ipynb`).  

3. **Data Integration**  
   - Merged scraped data with economic indicators (`all_data.csv` → `data_final.csv`).  

4. **Modeling**  
   - Price prediction using Jupyter Notebook (`real-estate_prediction.ipynb`).  

---

## 🔍 Key Files  
| File | Purpose |  
|------|---------|  
| `WebScraping_*.ipynb` | Scraping scripts for different property types |  
| `otodom_*_offers.csv` | Raw scraped data |  
| `data_final.csv` | Cleaned dataset for modeling |  
| `real-estate_prediction.ipynb` | Machine learning pipeline |  

---

## 📊 Languages & Tools  
- **Jupyter Notebook** (100% of code)  
- Python libraries: Pandas, Geopy, Scikit-learn, BeautifulSoup  
- Data sources: Otodom, public economic datasets  

---

## 👥 Team Equilibrium  
- [Oleksand Husiev]([https://github.com/user1](https://github.com/SSSHANKS))  
- [Maksym Chumachenko]([https://github.com/user2](https://github.com/ScR1Bl))  
- [Denys Solodov]
- [Petro Melnyk]
---

## 🔧 Setup  
```bash  
git clone https://github.com/your-repo/LionsDenPreselectionTask.git  
pip install -r requirements.txt  # (add if needed)  
```  
Run notebooks in order:  
1. WebScraping → 2. Coordinates → 3. real-estate_prediction  

---
