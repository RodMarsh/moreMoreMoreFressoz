# Energy Consumption: exploring Jean-Baptiste Fressoz's history of energy accumulation not transition

This repository provides R code and visualisations for a brief exploration of global energy consumption trends using data from Our World in Data to examine Jean-Baptiste Fressoz's contention in his  *More, More, and More: An All-Consuming History of Energy* that:

> [A]ll primary energies have grown together and why they have accumulated without replacing each other. Instead of considering energies as separate entities in competition with each other, it reveals the history of their entanglement and interdependence. [...] After two centuries of ‘energy transitions’, humanity has never burned so much oil and gas, so much coal and so much wood. [...] There is no reason why historians should choose transition as the main motif of their accounts. Energy sources are as much symbiotic as they are in competition, and their symbiotic relationships explain why, over the course of the nineteenth and twentieth centuries, primary energy sources tended to add up rather than substitute each other. (pp.1-10)

The final plot includes plots for:

1. **Indexed Growth**: Comparing the relative growth rates of primary energy sources since their first recorded use.
2. **Proportional Change**: Showing changes in the proportion each energy source contributes to total global energy use over time.

## Data Source

- [Global Direct Primary Energy Consumption](https://ourworldindata.org/grapher/global-primary-energy) from Our World in Data.

## Repository Contents

- `fressozOWDglobalEnergyConsumption.rmd`: RMarkdown workbook for data processing and generating plots.
- `combined_growth_proportion_plot.pdf`: Generated plot.

## How to Use

- Clone this repository.
- Ensure you have the following packages installed in R.
  - tidyverse
  - readr
  - stringr
  - jsonlite
  - patchwork
  - ggtext 
- Run the scripts in `fressozOWDglobalEnergyConsumption.rmd` to reproduce the visualisations.

## Licence

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

