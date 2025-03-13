# Benchmarks for the Salvage Logging under Uncertainty Problem 

This repository constains the supplemental materials for the article:

*Improving Salvage Logging Decisions in the Presence of Estimation Errors through Chance Constraints*

by Constanza Lorca, [Rodrigo A. Carrasco](https://www.raxlab.science/members/rodrigo-a.-carrasco/)

Paper information available here: [Link]

## Version 1.0

Update 2025-03-12
  - Uploaded datasets containing different numbers of forest stands and teams.

## **Files in this repository:**
  - Datasets/: Contains multiple datasets representing different salvage logging problem instances. Each datset includes information about forest stands, logging teams, inventory, and financial data.
  - The following datasets are available:
    - example_S3.xlsx
    - example_S12.xlsx
    - example_S16.xlsx
    - example_S20.xlsx
      
Each dataset follows the same structure, with the number in the filename indicating the number of forest stands included in that particular dataset.

## **Dataset Sheets:**
| Sheet Name         | Description  |
|--------------------|--------------|
| Stands | Contains details about each forest stand, including its ID, wood inventory, wood posts, and logs quantities. |
| Teams | Information about available logging teams, including their type (insurance, internal, external). |
| Financial | Includes operational costs, wood selling price, and interest rate return. |
| Production | Information about each team's production rate in each stand. |
| Sawmills | Contains details about each samill, including its ID, maximum input capacity, performance, variable cost, and type. |
| Squads | List of squads, including their type. |
| Time | List of liabilities for each time period. |


