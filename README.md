# Melbourne-Housing-Market-project


This project analyzes the Kaggle Melbourne Housing Market dataset to identify the most important features affecting house prices in Melbourne, Australia.

Research Question
What are the most important features affecting house prices?

Dataset
The dataset is sourced from Kaggle: Melbourne Housing Market. It contains ~13,580 rows and 21 columns, including features like Rooms, Price, Distance, Landsize, BuildingArea, and YearBuilt.

How to Access the Dataset
Visit the Kaggle dataset page.
Download Melbourne_housing_FULL.csv.
Place the CSV file in the data/ directory or specify the path in the notebook.

Alternatively, use the Kaggle API:
pip install kaggle
kaggle datasets download -d anthonypino/melbourne-housing-market
unzip melbourne-housing-market.zip

Install dependencies:
pip install -r requirements.txt

Dependencies
See requirements.txt for a list of Python packages.

Key Findings
Size and Quality: Larger houses (by square footage) and higher-quality homes command higher prices.
Location and Age: Newer houses and proximity to the city center increase prices.
Additional Features: Garage size and renovations positively impact prices.
Pricing Insights: Most houses are sold between $100,000-$200,000, with significant price variation.
