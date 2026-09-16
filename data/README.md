# Data

Raw datasets are intentionally not included in this repository because the OpenStreetMap extract used for the project is approximately 2.2 GB.

The notebook expects these files inside this directory:

```text
data/
├── flat_data.json
├── us_food.csv
└── zip_county_crosswalk.csv
```

## Sources used in the project

- **OpenStreetMap** — restaurant, fast-food, and cafe points of interest with ZIP/postcode information.
- **U.S. Census / Food Environment data** — county-level demographic and restaurant-supply features such as household income, population, poverty, obesity, age distribution, and cuisine counts.
- **HUD ZIP-to-County Crosswalk** — maps ZIP codes to county FIPS codes using residential ratios.

Before reproducing the analysis, obtain the datasets from their original providers and place them under the filenames shown above.
