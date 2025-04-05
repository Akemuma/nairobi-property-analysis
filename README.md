# 🏠 Nairobi Property Data Analysis 📊

Dive into the Nairobi real estate market with this project! We create a simulated dataset 📝, clean it up 🧼, analyze the trends 📈, and visualize the insights 🗺️.

## 🚀 Project Overview

This repo is your one-stop shop for exploring Nairobi property data. It includes:

* **`nairobi_properties.db` 💾:** A SQLite database with our simulated Nairobi property listings.
* **`nairobi_properties_analysis.ipynb` 📓:** A Jupyter Notebook that does all the magic: data generation, cleaning, analysis, and visualization!

## 🏁 Getting Started

1.  **Clone the Repo 📥:**

    ```bash
    git clone [https://github.com/Akemuma/nairobi-property-analysis](https://github.com/Akemuma/nairobi-property-analysis)
    cd nairobi-property-analysis
    ```

2.  **Run the Notebook 🏃‍♂️:**

    * Make sure you have Python, Pandas 🐼, SQLite, Matplotlib 📈, and Seaborn 🌊 installed.
    * Open `nairobi_properties_analysis.ipynb` in Jupyter Notebook/Lab.
    * Hit "Run All" 🎬! This will:
        * Create `nairobi_properties.db` 🛠️ (if needed).
        * Generate 10,000 property listings 🏡.
        * Clean the data 🧹.
        * Analyze the market 🧐.
        * Show you cool visualizations 🤩.

3.  **See the Results 👀:**

    * Check out the charts and graphs in the notebook!
    * The `nairobi_properties.db` file will be in the same folder.

## 📂 Project Structure
nairobi-property-analysis/
├── nairobi_properties.db 💾
├── nairobi_properties_analysis.ipynb 📓
└── README.md 📄

## 📝 Data Description

Our simulated dataset includes:

* `property_id` 🔑: Unique ID for each property.
* `property_name` 🏷️: Property name.
* `location` 📍: Nairobi neighborhood.
* `property_type` 🏠: Apartment, House, Condo, etc.
* `bedrooms` 🛏️: Number of bedrooms.
* `bathrooms` 🛁: Number of bathrooms.
* `price` 💰: Price (KES).
* `square_meters` 📏: Property size.
* `listing_date` 📅: Listing date.
* `latitude` 🌎: Latitude.
* `longitude` 🌍: Longitude.
* `price_per_sqm` 💸: Price per square meter.

## 📊 Visualizations

We've got charts galore! 🥳:

* Price distribution 📈.
* Price vs. size 📏 vs. 💰.
* Property count by location 🗺️.
* Price by property type 🏠 vs. 💰.
* Geographical price map 📍 with color gradients 🌈.

## 📦 Dependencies

* Python 3.x 🐍
* Pandas 🐼
* SQLite3 🗄️
* Matplotlib 📈
* Seaborn 🌊

## 🤝 Contributing

Got ideas? Pull requests welcome! 🚀 Let's make this project even better.
