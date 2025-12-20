# 5-Year Financial Statement Analysis Project

## Overview

This project presents a comprehensive financial statement analysis spanning five years, utilizing audited annual report data to evaluate organizational performance across multiple dimensions. The analysis integrates financial ratio computation with rigorous statistical methods to generate evidence-based insights into liquidity, profitability, and operational efficiency trends.

## Objectives

- Evaluate liquidity, profitability, and operating efficiency trends over a 5-year period
- Identify patterns and relationships among key financial indicators
- Assess the stability and volatility of financial performance metrics
- Determine predictive relationships between financial ratios using statistical modeling

## Methodology

### Data Collection & Preparation

**Data Source**: Secondary data extracted from published audited annual reports

**Data Processing Steps**:
- Collected financial data from official annual reports across five consecutive years
- Transformed raw financial statements into clean, analysis-ready formats
- Structured data into year-wise comparison tables for temporal analysis
- Ensured data quality and consistency across reporting periods

### Financial Ratio Analysis

Computed and interpreted key financial ratios across three dimensions:

**Liquidity Ratios**
- Current Ratio (CR)
- Quick Ratio
- Cash Ratio

**Profitability Ratios**
- Return on Equity (ROE)
- Return on Assets (ROA)
- Net Profit Margin (NPM)
- Gross Profit Margin (GPM)

**Efficiency Ratios**
- Asset Turnover Ratio (ATR)
- Inventory Turnover
- Receivables Turnover

### Statistical Analysis

#### Descriptive Statistics

For each financial ratio, calculated:
- **Mean**: Average performance across the 5-year period
- **Standard Deviation (SD)**: Absolute variability of performance
- **Coefficient of Variation (CV)**: Relative volatility measure (SD/Mean × 100)

**Purpose**: Assess consistency and stability of financial metrics; identify periods of high volatility or stability

#### Correlation Analysis

Conducted Pearson correlation analysis to examine relationships among financial indicators:

**Key Findings**:
- Strong positive association between profitability indicators (ROE, ROA, NPM)
- Inverse relationship observed between efficiency and profitability metrics
- Identified interconnected performance drivers

#### Regression Analysis

Built multiple regression models to explore predictive relationships:

**Dependent Variables**:
- Return on Assets (ROA)
- Return on Equity (ROE)
- Net Profit Margin (NPM)

**Independent Variables (Predictors)**:
- Current Ratio (CR)
- Gross Profit Margin (GPM)
- Asset Turnover Ratio (ATR)

**Analysis Focus**:
- Directional impact of predictors on profitability measures
- Explanatory power (R²) of models
- Statistical significance of relationships
- Coefficient interpretation and practical implications

## Key Insights

### Performance Trends
- Year-over-year evolution of liquidity, profitability, and efficiency metrics
- Identification of improving or deteriorating financial health indicators

### Stability Assessment
- High CV values indicate volatile/unstable performance
- Low CV values suggest consistent performance patterns

### Relationship Patterns
- Profitability indicators move together (positive correlation)
- Trade-offs observed between operational efficiency and profit margins
- Liquidity impacts on overall financial performance

### Predictive Relationships
- Quantified impact of liquidity and efficiency on profitability
- Identified key drivers of financial performance through regression coefficients

## Tools & Techniques

- **Data Processing**: Excel/Python for data transformation and cleaning
- **Statistical Analysis**: Descriptive statistics, correlation matrices, regression modeling
- **Visualization**: Trend charts, scatter plots, correlation heatmaps
- **Validation**: Cross-verification with audited financial statements

## Project Structure

```
├── data/
│   ├── raw/                 # Original annual report data
│   └── processed/           # Clean, analysis-ready datasets
├── analysis/
│   ├── ratios/             # Financial ratio calculations
│   ├── descriptive/        # Mean, SD, CV computations
│   ├── correlation/        # Correlation analysis results
│   └── regression/         # Regression models and outputs
├── visualizations/         # Charts, graphs, and dashboards
├── reports/               # Final analysis reports and interpretations
└── README.md
```

## Getting Started

### Prerequisites

- Excel 2016 or later / Python 3.8+
- Statistical analysis software (optional): R, SPSS, or Python libraries (pandas, numpy, scipy, statsmodels)
- Basic understanding of financial ratios and statistical concepts

### Installation

1. Clone this repository or download the project files
2. Ensure all data files are placed in the `data/raw/` directory
3. Install required Python packages (if using Python):
   ```bash
   pip install pandas numpy scipy statsmodels matplotlib seaborn
   ```

### Usage

1. **Data Preparation**: Place audited annual reports in `data/raw/`
2. **Ratio Calculation**: Run analysis scripts in `analysis/ratios/`
3. **Statistical Analysis**: Execute descriptive, correlation, and regression analyses
4. **Review Results**: Check `reports/` directory for final outputs and interpretations

## Conclusions

The integrated approach combining traditional financial ratio analysis with statistical methods provides a robust framework for understanding organizational financial performance. The use of correlation and regression analysis strengthens conclusions beyond descriptive observations, enabling evidence-based decision-making and strategic planning.

## Limitations & Considerations

- Analysis based on historical data; future performance may differ
- Limited to publicly available audited financial information
- Industry-specific contexts should be considered when interpreting results
- Statistical relationships indicate association, not necessarily causation

## Future Enhancements

- Extend analysis to include industry benchmarking
- Incorporate forecasting models for predictive insights
- Add sensitivity analysis for key financial drivers
- Expand dataset to include more recent fiscal years

## Contributing

Contributions to enhance the analysis methodology or expand the scope are welcome. Please submit pull requests or open issues for discussion.

## License

This project is available for educational and research purposes.

## Contact

For questions or collaboration opportunities, please reach out through the repository's issue tracker.

---

**Project Duration**: 5 fiscal years analyzed  
**Data Type**: Secondary data from audited annual reports  
**Analytical Approach**: Mixed methods (financial analysis + statistical modeling)  
**Last Updated**: Decembe
