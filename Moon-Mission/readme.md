# Moon Mission Dashboard

## Overview
The Moon Mission Dashboard is an interactive visualization built using Power BI, offering insights into the history of lunar missions from 1958 to 2023. It provides detailed information about various missions, their outcomes, and statistics related to the countries involved in these lunar endeavors. The dashboard is designed to help users explore the successes, failures, and operational missions aimed at reaching and exploring the Moon.

## Features
- **Mission Timeline**: A slider to filter lunar missions based on the year range (1958-2023).
- **Mission Outcome Distribution**: Pie and bar charts to visualize the different outcomes (e.g., Successful, Launch Failure, Spacecraft Failure).
- **Mission Count Overview**: KPIs displaying the total number of missions, successful missions, and launch failures.
- **Missions by Country**: A bar chart showing the number of moon missions launched by each country.
- **Detailed Mission List**: A table listing mission outcomes and their corresponding details, providing a quick view of mission names and their statuses.

## Data
The dashboard uses data from a CSV file containing detailed information about moon missions conducted by various countries. The dataset includes the following details:
- **Mission Name**: The official name of each lunar mission.
- **Outcome**: The result of the mission (e.g., Successful, Launch Failure, Operational).
- **Country**: The country that launched the mission.
- **Year**: The year the mission took place.

The `Moonlanding.csv` file used for this dashboard is included in the repository. You can explore this dataset to understand the structure and the details used in the visualizations.

## Insights
- The dashboard shows the total number of lunar missions conducted and their outcomes, with a significant percentage of missions being successful.
- It highlights the leading countries in lunar exploration, with the United States and Soviet Union being the most active participants.
- The visualizations help track the progression of lunar missions over time and compare outcomes across different space agencies.

## Installation

To set up and view the Moon Mission Dashboard on your local system, follow the steps below:

### Prerequisites
- **Power BI Desktop**: Ensure you have Power BI Desktop installed. You can download it [here](https://powerbi.microsoft.com/en-us/desktop/).
- **Git** (optional): If you want to clone the repository using Git, make sure you have Git installed. You can download it [here](https://git-scm.com/).

### Steps

1. **Clone the Repository**:
   - If you have Git installed, open your terminal or command prompt and run the following command to clone the repository:
     ```bash
     git clone https://github.com/shubhy04/Dashboards.git
     ```
   - Alternatively, you can download the repository as a ZIP file from GitHub by clicking the "Code" button on the repository page and selecting "Download ZIP".

2. **Open the Power BI File**:
   - Locate the `Moon mission.pbix` file in the Moon-Mission directory cloned/downloaded repository.
   - Double-click the `.pbix` file to open it in Power BI Desktop. If Power BI Desktop is not set as the default application for `.pbix` files, you can open Power BI Desktop first and then use the `File -> Open` option to browse and open the file.

3. **Ensure the Background Image is Loaded**:
   - The dashboard uses a background image (`wall.jpg`) to create a space-themed aesthetic. The image should be included in the repository alongside the Power BI file. Ensure the path to the image is correctly set in the Power BI file's background settings.

4. **Refresh the Data** (if needed):
   - The dashboard uses the `Moonlanding.csv` file as its data source. If you make any changes to the CSV file or want to update the data, click on the `Refresh` button in the ribbon at the top of the Power BI window.

5. **Explore the Dashboard**:
   - Use the interactive elements such as filters, sliders, and visualizations to explore the data and gain insights into moon missions from 1958 to 2023.

### Additional Notes
- Ensure that your system meets the minimum requirements for running Power BI Desktop. A minimum of 4 GB RAM and a 64-bit version of Windows are recommended for optimal performance.
- Make sure you have an internet connection to download Power BI Desktop and Git (if you choose to use Git for cloning).

## Project Structure
- `Moon mission.pbix`: The main Power BI file containing the dashboard and all visualizations.
- `Moonlanding.csv`: The dataset used for building the dashboard, including detailed information about each lunar mission.
- `wall.jpg`: The background image used in the dashboard to create a space-themed aesthetic.
- `README.md`: Documentation file explaining the dashboard.

## Contact
For any questions or feedback, feel free to contact:
- **Name**: Shubham Sawant
- **Email**: [sawantshubham861@gmail.com](mailto:sawantshubham861@gmail.com)
- **LinkedIn**: [linkedin.com/in/shubhy04](https://linkedin.com/in/shubhy04)

