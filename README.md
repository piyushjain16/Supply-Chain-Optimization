# Supply Chain Optimization using NP-Hard Approximation

## Introduction

This project optimizes supply chain logistics using NP-Hard approximation methods, focusing on efficient production forecasting and strategic plant placement.

## Highlights

1. **Algorithm Design**: Developed a greedy algorithm for production forecasting and supply chain optimization.
2. **Cost Function**: Custom-designed to minimize forecasting errors, utility costs, and transportation expenses, achieving a score improvement from 37.2 to 80.4.
3. **Real-World Relevance**: Included practical constraints like minimum production processing requirements and Partial Processing.

## Project Layout

The project is divided into two main parts, with input data stored in the `/Dataset` folder.

### Biomass Forecasting

- **Script**: `Biomass_forecast_generator.ipynb`
- **Output**: `/Biomass Results/Biomass_forecast.csv`
- **Approach**: Utilizes locality of reference to generate features and predict biomass production.

### Supply Chain Optimization

- **Script**: `Biomass_supply_chain_optimizer.ipynb`
- **Output**: `/Biomass Results/submission.csv`
- **Method**: 
  - Calculate depot and refinery locations using MST for clustering.
  - Refine locations using fractional knapsack for optimal results.

## Getting Started

1. **Clone the Repo**:
    ```bash
    git clone https://github.com/piyushjain16/supply-chain-optimization.git
    cd supply-chain-optimization
    ```

2. **Execute Forecast**:
    Run `Biomass_forecast_generator.ipynb` to generate biomass forecasts.

3. **Run Optimization**:
    Execute `Biomass_supply_chain_optimizer.ipynb` to optimize the supply chain based on forecast results.

## Outcome

Achieved significant improvement in supply chain efficiency with a performance boost from a baseline score of 37.2 to 80.4.

## License

This project is under the MIT License.
