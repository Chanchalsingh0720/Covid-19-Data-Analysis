# COVID-19 Dataset (March 2020 - July 2020)

This repository contains a comprehensive dataset tracking the COVID-19 pandemic from March 2020 to July 2020. The data captures the spread and impact of the virus across various regions worldwide.

## Dataset Overview

The dataset includes the following columns:

- **province_state**: The state, province, or region within a country.
- **country_region**: The country or region where the data was recorded.
- **date**: The date of the record in `DD-MM-YYYY` format.
- **latitude**: The latitude coordinate of the region.
- **longitude**: The longitude coordinate of the region.
- **location_geom**: Geometric representation of the location for mapping purposes.
- **confirmed**: The number of confirmed COVID-19 cases.
- **deaths**: The number of deaths attributed to COVID-19.
- **recovered**: The number of recovered cases.
- **active**: The number of active COVID-19 cases (calculated as `confirmed - deaths - recovered`).
