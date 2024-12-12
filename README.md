# Boston Airbnb Analysis App

## Overview
The "Boston Airbnb Analysis App" is a Shiny web application that explores Airbnb listings in Boston. This interactive tool provides insights into price distributions, neighborhood vibes, room types, and income estimates, helping hosts, travelers, and policymakers better understand Airbnb trends in the city.

## Features
- **Interactive Map:** Visualize Airbnb listings by price, room type, and availability.
- **Neighborhood Insights:** Generate word clouds to capture the unique "vibes" of each neighborhood.
- **Price Analysis:** Explore price distributions and average income estimates.
- **Room Type Breakdown:** Compare the number of listings and average prices across room types.

## Technologies Used
- **Shiny:** For creating an interactive web application.
- **R Programming Language:** For data processing and visualization.
- **Libraries:**
  - `shiny`: For app development.
  - `leaflet`: For interactive maps.
  - `tidyverse`: For data manipulation.
  - `wordcloud2`: For generating word clouds.
  - `ggplot2`: For visualizing data trends.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Open the `Shiny_app_NOV.R` file in RStudio.
3. Ensure you have all the required libraries installed:
   ```R
   install.packages(c("shiny", "tidyverse", "wordcloud2", "leaflet", "ggpubr", "ggthemes"))
   ```
4. Run the application by clicking the **Run App** button in RStudio.

## Usage
1. **Neighborhood Selection:** Use the dropdown menu to select a specific neighborhood or view all.
2. **Interactive Map:** Adjust sliders for price and ratings to filter listings and see updated results on the map.
3. **Word Cloud:** Explore common words in neighborhood overviews to understand the vibe of each area.
4. **Visualizations:** View distribution plots for price, room types, and monthly income.

## Demo
Below are key visualizations from the app:
- Interactive Map
![Interactive Map](path/to/map_image.png)
- Price Distribution
![Price Distribution](path/to/price_distribution_image.png)
- Word Cloud
![Word Cloud](path/to/word_cloud_image.png)

## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
**Sahil Gawande**

For inquiries or collaboration opportunities, please reach out.
