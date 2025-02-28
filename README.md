# Visualizing Africa's Economic Journey: Data Study

## Project Overview
This project analyzes economic and financial crisis indicators across 13 African countries using data visualization techniques. The study examines the relationship between various economic factors including exchange rates, inflation, and different types of financial crises, with particular attention to the impact of independence on economic stability.

## Dataset
The dataset contains historical economic data for 13 African countries.

The data spans multiple decades and includes the following key variables:
- Exchange rates against USD
- Annual inflation (CPI)
- Systemic crisis indicators
- Domestic debt default indicators
- Sovereign external debt default indicators
- Currency crisis indicators
- Inflation crisis indicators
- Banking crisis indicators
- Independence status

## Key Visualizations

### 1. Currency Performance Against USD
Tracks each country's exchange rate against the US dollar over time, with a vertical dotted line marking the year of independence. This visualization reveals how currencies have performed before and after independence.

### 2. Crisis Indicators by Country
A series of countplots showing the distribution of different types of economic crises across countries, highlighting which nations have experienced the most frequent crises of each type.

### 3. Annual Inflation Trends
Displays inflation patterns for each country over time, with independence marked by a vertical line, demonstrating the relationship between political sovereignty and inflation stability.

### 4. Correlation Heatmap
The correlation analysis reveals several important relationships between economic variables:

- **Currency and Inflation Crises**: Strong positive correlation, demonstrating how currency devaluations often trigger inflation spikes
- **Debt Default Patterns**: Meaningful correlation between domestic and sovereign external debt defaults, suggesting that countries experiencing one type of default are at higher risk for the other
- **Post-Independence Effects**: The independence variable shows correlation with systemic crises, suggesting newly independent nations face distinct economic challenges
- **Crisis Contagion**: Systemic crises correlate with several other crisis indicators, highlighting how financial problems tend to spread across economic sectors
- **Exchange Rate Relationships**: Exchange rates show expected correlations with currency crises and moderate relationships with other economic indicators
- **Temporal Trends**: The year variable correlations suggest some historical patterns in crisis occurrence that may reflect global economic cycles

## Key Findings

1. **Independence Impact**: Many countries show significant changes in exchange rate volatility and inflation patterns following independence, suggesting that political sovereignty has substantial economic consequences.

2. **Crisis Clustering**: The data reveals that economic crises tend to occur in clusters, with one type of crisis often coinciding with or leading to other types of financial distress.

3. **Regional Patterns**: Countries within similar geographical regions sometimes display comparable economic patterns, particularly during global economic downturns.

4. **Currency Stability**: Currency stability appears to vary widely across the continent, with some nations maintaining relatively stable exchange rates while others experience dramatic fluctuations.

5. **Inflation Volatility**: Post-independence inflation patterns demonstrate considerable variation, with some countries achieving stability while others face prolonged periods of high inflation.

## Technical Implementation
This project uses Python with the following libraries:
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- NumPy for numerical operations

The visualization techniques include:
- Line plots with scatter points for time-series data
- Countplots for categorical comparisons
- Correlation heatmaps for relationship analysis
