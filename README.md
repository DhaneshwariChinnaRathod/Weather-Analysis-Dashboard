# Weather Dashboard

An interactive **Power BI Weather Dashboard** for exploring current weather conditions, short-term forecasts, and air-quality indicators by location.

## Project Overview

This dashboard brings key weather and air-quality information together in one place. Users can select a location and review current conditions, forecast trends, and pollutant readings through a set of visual report pages.

## Dashboard Features

- **Location selection** to view weather information for a selected place.
- **Current weather summary**, including temperature and weather condition.
- **Weather metrics**, including:
  - Humidity
  - Wind speed
  - Visibility
  - Atmospheric pressure
  - UV index
  - Precipitation
- **Weather forecast** with average temperature by forecast date.
- **Rain probability** displayed using a 100% stacked bar visual.
- **Sunrise and sunset** forecast information.
- **Air-quality readings** for:
  - PM2.5
  - PM10
  - SO₂
  - NO₂
  - CO
  - O₃
- **Air-quality status and guidance**, including a PM10 status indicator and suggestion.
- **Multiple visual themes** across four report pages: Orange, Purple, Blue, and Shades.

## Tools Used

- Microsoft Power BI Desktop
- Power Query / Power BI data model
- DAX measures and calculated fields (where used in the report)

## Repository Contents

| File / Folder | Description |
|---|---|
| `Weather Dashboard.pbix` | Power BI report file |
| `Screenshots/` | Dashboard preview images (add this folder to the repository) |
| `README.md` | Project documentation |

## How to View the Dashboard

1. Download or clone this repository.
2. Open `Weather Dashboard.pbix` using **Microsoft Power BI Desktop**.
3. If Power BI asks you to configure or refresh a data connection, follow the prompts and provide the required source/API credentials.
4. Use the location selector and report visuals to explore the dashboard.

> **Note:** A `.pbix` file is an interactive Power BI report. GitHub can store the file, but it does not render the report as an interactive dashboard directly on the repository page. Open it in Power BI Desktop to interact with it.

## Screenshots

Add dashboard screenshots to a folder named `Screenshots` in the repository, then update the image paths below.

### Orange Theme
`Screenshots/orange-theme.png`

### Purple Theme
`Screenshots/purple-theme.png`

### Blue Theme
`Screenshots/blue-theme.png`

### Shades Theme
`Screenshots/shades-theme.png`

To display the images on GitHub, replace the text placeholders above with Markdown image links, for example:

```md
![Weather Dashboard - Orange Theme](Screenshots/orange-theme.png)
```

## Key Insights Available

The report is designed to help users quickly review:

- The selected location's current weather conditions.
- How forecast temperatures change across upcoming dates.
- The likelihood of rain during the forecast period.
- Key air pollutants and their displayed readings.
- The dashboard's air-quality status and related suggestion.

## Future Improvements

- Add a clear data-source and API description.
- Document the refresh frequency and any API limits.
- Add more forecast comparisons and historical weather trends.
- Improve mobile layout and accessibility.
- Add further air-quality indicators and location comparisons.

## Author

**Dhaneshwari Chinna Rathod**

---

If you find this project useful, feel free to star the repository.
