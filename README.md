# Traffic Accident Analysis

🔍 **Objective:** 
To analyze traffic accident data and identify patterns related to road conditions, weather, and time of day, and to visualize accident hotspots and contributing factors.

## Steps Taken:

### Data Loading and Cleaning:
- Loaded the traffic accident dataset and cleaned the data by handling missing values and irrelevant columns.
- Converted date columns to datetime format for better analysis.

### Exploratory Data Analysis (EDA):
- **Day of the Week Analysis:** Analyzed the distribution of accidents by day of the week.
- **Weather Conditions Analysis:** Examined the top weather conditions during accidents.
- **Severity Analysis:** Explored the distribution of accident severity levels.

### Visualization of Accident Hotspots:
- Utilized folium to create an interactive heatmap of accident hotspots across different locations.

### Identification of Contributing Factors:
- Performed a correlation analysis to understand the relationship between various factors like latitude, longitude, and speed limit.
- Visualized how severity varies with speed limit, latitude, and longitude.

## Key Visualizations:

### Accident Distribution by Day of the Week:
- Bar chart showing the number of accidents occurring on different days of the week.

### Top Weather Conditions for Accidents:
- Bar chart displaying the top weather conditions associated with traffic accidents.

### Accident Hotspots:
- Interactive heatmap highlighting the geographic locations with the highest accident frequencies.

### Contributing Factors:
- Correlation heatmap and box plots showing the relationship between accident severity and factors like speed limit, latitude, and longitude.

## Insights:

- **Peak Days:** Identified peak days during which accidents are most likely to occur.
- **Weather Impact:** Found significant weather conditions contributing to higher accident rates.
- **Hotspots:** Highlighted key geographic areas with high accident frequencies.
- **Contributing Factors:** Uncovered how different factors like speed limit, latitude, and longitude correlate with accident severity.

## Dataset

- **Name:** Car Accident Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/nextmillionaire/car-accident-dataset)

## Requirements

- Python 3.x
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Folium

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/traffic-accident-analysis.git
   cd traffic-accident-analysis
