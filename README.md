# Intel Data Center Energy Analysis

A Tableau-based analysis of regional U.S. energy production, demand, and renewable energy characteristics to support data center site selection.

## Project Overview

This project was completed as part of the Global Career Accelerator Data Analytics Track in collaboration with Intel's Sustainability Team.

The goal was to evaluate U.S. regions as potential locations for a new data center by examining energy availability, demand, renewable energy adoption, generation stability, and regional energy-source composition.

The analysis was developed in Tableau and culminated in a recommendation of the **Central region** as the strongest candidate for further site investigation.

## Business Question

**Which U.S. region provides the most favorable energy characteristics for locating a new data center?**

The analysis considered several factors relevant to large-scale data center operations:

- Energy production relative to demand
- Renewable energy availability
- Regional energy-source composition
- Seasonal supply and demand
- Hourly changes in generation
- Stability of regional energy infrastructure

## Analysis

### Net Energy Production

A calculated field was created to measure the difference between regional generation and demand:

`Net Production = SUM(Net Generation) - SUM(Demand)`

The analysis identified the following regions as net energy producers:

- Mid-Atlantic
- Northwest
- Southwest
- Central
- Southeast

This provided an initial way to identify regions whose generation exceeded their existing energy demand.

### Supply and Demand Over Time

An interactive Tableau visualization was developed to compare demand and net generation by region and time period.

This made it possible to examine seasonal variation and identify periods when individual regions experienced greater energy surpluses or tighter supply-demand conditions.

### Renewable Energy

Renewable generation was calculated from solar, wind, and hydropower generation and compared with total net generation.

The three regions with the highest percentage of renewable generation were:

1. Northwest
2. Central
3. California

### Energy Source Composition

Regional energy portfolios were also examined by source, including wind, natural gas, coal, nuclear, solar, and hydropower.

The **Central and Northwest regions** stood out as regions where renewable energy represented a particularly significant component of overall generation.

### Hourly Generation Trends

Hourly changes in generation were analyzed to examine the stability and timing of individual energy sources.

This provided another dimension for evaluating regional infrastructure beyond aggregate generation totals, since a data center requires not only sufficient energy but dependable availability over time.

## Recommendation

Based on the combined analysis, I recommended the **Central region** for further investigation as a potential data center location.

Several characteristics contributed to this recommendation:

- Positive net energy production
- Strong and growing wind-energy infrastructure
- High renewable-energy utilization
- Relatively stable generation patterns
- Lower population density and associated demand
- Geographic characteristics potentially favorable to large-scale infrastructure

The **Northwest** was identified as another strong candidate because of its renewable-energy profile and positive net production, although environmental and land-use considerations made the Central region the preferred recommendation.

## Tools & Skills

- Tableau
- Data visualization
- Calculated fields
- Exploratory data analysis
- Energy supply and demand analysis
- Time-series visualization
- Business recommendation development
- Data storytelling

## Project Artifacts

The original analysis was performed in a cloud-hosted Tableau environment through the Global Career Accelerator. The original workbook and source environment are no longer available.

The [`docs`](docs/) directory contains the final submitted project report, including screenshots of the original Tableau visualizations, methodology, findings, and recommendation.

## Project Context

**Program:** Global Career Accelerator — Data Analytics Track  
**Industry collaboration:** Intel Sustainability Team  
**Completed:** August 2024  
**Author:** Jeremy Joubert
