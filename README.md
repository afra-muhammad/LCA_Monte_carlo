# LCA_Monte_carlo
## Monte Carlo Simulation of Shower Carbon Emissions

This project uses Monte Carlo simulation to estimate carbon emissions from household showers. It models uncertainty in shower duration, heating systems, and water treatment sources to provide a realistic distribution of CO₂ emissions.

## Project Structure
This project is divided into severak folders, each cointaining a specific set of resources related to different phases of project.

## 1- Data 
This folder cointains the CSV files with the dataset used for this project.

## 2- Monte__carlo_Analysis 
This folder cointains Jupyter notebook that were used to perform monte carlo analsis of the dataset(jupyter notebook for exploration, testing, and visualisation). This folder also cointainssimulation results.


## Project Overview
- Shower duration is modeled with a right-skewed log-normal distribution centered around ~10 minutes.

- Heat-source emissions show that low-carbon systems (e.g., borehole heat pumps) dominate near-zero emissions, while gas and oil heating cause most mid-to-high emissions (0.8–2.5 kg).

- Water-source emissions cluster strongly near 0 kg due to efficient treatment methods. Rare higher-emission cases (up to ~1.4 kg) come mainly from seawater reverse osmosis (RO), which is known for higher energy use and greenhouse gas impact.

- Renewable / low-carbon sources consistently contribute less to the overall footprint.

## Key Insight

Although most shower-related emissions are low, fossil-fuel heating and energy-intensive RO water treatment disproportionately drive the higher end of CO₂ output. Monte Carlo simulation effectively captures this variability and identifies the main contributors to environmental impact.

