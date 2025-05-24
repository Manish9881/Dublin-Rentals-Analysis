# Dublin Rentals Analysis 🏙️

This project analyzes historical Dublin rental listing data to uncover trends in pricing, property features, lease durations, and neighborhood patterns. The data was originally scraped from a university-hosted website that is no longer publicly accessible.

## 📁 Project Structure

- `Task1.ipynb` – Web scraping logic used to originally collect rental data across multiple quarters *(now based on archived content)*
- `Task2.ipynb` – Data cleaning, preprocessing, and exploratory analysis including pricing trends and amenity impacts
- `all_rental_records.csv` – Final processed dataset of Dublin rental listings

## 🧰 Technologies Used

- Python 3
- `BeautifulSoup` for HTML parsing
- `urllib` for archived web content requests
- `pandas`, `numpy` for data wrangling
- `matplotlib` for data visualization
- `re` for regex-based preprocessing

## 🔍 Key Insights

- **Price Range:** €670 – €7,640, with a median around €2,090
- **Property Size:** Most listings are 1–2 bedroom, 1–2 bathroom
- **Amenities:** Listings with gardens or parking command a higher price (~€2,000 more)
- **Lease Lengths:** 12-month leases dominate; shorter leases are rare but slightly more expensive
- **Seasonality:** Prices tend to rise toward Q4; Q3 may offer lower average prices
- **Location Impact:**
  - **North Dublin**: More budget-friendly
  - **South Dublin**: High-end market (notably D4, D6, D16)
  - **Hotspots**: Dublin 24, 17, and 15 offer good rental value

## 👨‍💻 Target Audiences

- **Renters** – Make informed decisions based on lease length, amenities, and timing
- **Investors** – Evaluate return potential by property feature and location
- **Market Analysts** – Identify seasonal and geographic rental trends

## 📈 Future Extensions

- Integrate geographic visualizations (e.g., postal code heatmaps)
- Train ML models to predict rental prices
- Extend analysis to include more recent datasets (if available)

## 📬 Contact

Created by **Manish Tawade** 
Repository maintained for educational and archival analysis purposes.

---

> ⚠️ Note: The original data source is no longer online. The dataset used here is a snapshot captured during the course of a previous academic module.
