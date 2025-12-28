# U.S. Agricultural Trade Analysis Project

## Project Charter

**Objective**: Analyze U.S. agricultural trade with middle-income countries to identify value chain opportunities for increasing exports of processed goods.

**Scope**: Focus on middle-income countries as defined by World Bank classification. Use 2020 trade data snapshot.

**Team**: University research team simulating a trade analysis unit.

**Deliverables**:
1. Identification of high-potential middle-income markets for U.S. processed agricultural exports.
2. Policy recommendations tailored to specific country contexts.
3. Documentation of analysis workflow and findings.

**Timeline**: 4-week research sprint.

**Repository Structure**:
- `data/`: Contains trade datasets.
- `findings/`: Analysis reports per country.
- `scripts/`: Data processing scripts (optional).
- `README.md`: Project overview and charter.

## Getting Started

The dataset `trade_data_2020.csv` contains the following columns:
- `Country`: Partner country name
- `Income_Level`: Income classification (High, Middle, Low)
- `Product`: Agricultural product
- `Processing_Level`: Raw, Semi-Processed, or Processed
- `US_Export_Value`: Value of U.S. exports to the partner country (USD)
- `Partner_Country_Total_Imports`: Total imports of the product by the partner country (USD)

## Issues and Workflow

All analysis tasks are tracked as GitHub Issues. Each analysis follows a branch-per-country model with pull requests for review.