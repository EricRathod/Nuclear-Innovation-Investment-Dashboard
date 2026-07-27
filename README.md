# Nuclear Innovation Investment Dashboard

A strategic technology-assessment and commercialization portfolio project that evaluates emerging nuclear-industry opportunities using Python and Power BI.

The project compares ten technology areas across market potential, strategic fit, safety impact, technical readiness, partnership potential, financial attractiveness, regulatory complexity, estimated investment, and commercialization timeline.

> **Disclaimer:** All scores, costs, revenue estimates, savings, timelines, and recommendations are hypothetical assumptions created for portfolio demonstration. They do not represent Kinectrics or any other company's internal data, forecasts, or investment decisions.

## Business Question

Which emerging nuclear technologies offer the strongest combination of strategic value, market potential, safety impact, technical readiness, and commercialization feasibility?

## Dashboard Pages

### 1. Executive Overview

- Technologies evaluated
- Highest opportunity score
- Total estimated CAPEX
- Average three-year ROI
- Top technology
- Opportunity ranking
- CAPEX versus net annual benefit
- Priority and risk filters

### 2. Financial and Commercialization Analysis

- Total annual revenue and cost savings
- Average payback and development time
- Three-year ROI comparison
- Payback-period comparison
- CAPEX versus net annual benefit
- Detailed financial table

### 3. Strategic Roadmap

- Technology readiness versus market potential
- Strategic fit, safety, and partnership comparison
- Development timeline
- Recommended action and potential partners

## Dashboard Preview

### Executive Overview

![Executive Overview](images/executive-overview.png)

### Financial Analysis

![Financial Analysis](images/financial-analysis.png)

### Strategic Roadmap

![Strategic Roadmap](images/strategic-roadmap.png)

## Methodology

The weighted opportunity score uses the following criteria:

| Criterion | Weight |
|---|---:|
| Strategic fit | 25% |
| Market potential | 20% |
| Safety impact | 20% |
| Technology readiness | 15% |
| Partnership potential | 10% |
| Financial attractiveness | 10% |

Regulatory complexity and risk are displayed separately to preserve visibility into implementation constraints.

## Demonstration Findings

- **Medical Isotope Production** has the highest opportunity score at **9.60/10**.
- **Advanced Condition-Monitoring Sensors** have the fastest estimated payback at approximately **0.57 years**.
- Four technologies meet the short-term pilot criteria: robotic inspection, condition-monitoring sensors, AI-powered visual inspection, and digital twins/VR.
- The illustrative portfolio contains **C$14.25M** in CAPEX assumptions and **C$13.35M** in annual revenue assumptions.

These findings are outputs of the hypothetical scoring and financial model and require real engineering, safety, regulatory, customer, and financial validation before use in an actual decision.

## Repository Structure

```text
Nuclear-Innovation-Investment-Dashboard/
├── data/
│   ├── Nuclear_Technology_Investment_Dataset.csv
│   └── Nuclear_Technology_PowerBI_Ready.csv
├── notebooks/
│   └── Nuclear_Technology_Investment_Analysis.ipynb
├── images/
│   ├── executive-overview.png
│   ├── financial-analysis.png
│   └── strategic-roadmap.png
├── powerbi/
│   └── Nuclear_Innovation_Investment_Dashboard_Eric_Rathod.pbix
├── .gitignore
├── README.md
└── requirements.txt
```

## Tools

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Microsoft Power BI
- Google Colab

## Run the Analysis

1. Open `notebooks/Nuclear_Technology_Investment_Analysis.ipynb` in Google Colab or Jupyter.
2. Make sure `data/Nuclear_Technology_Investment_Dataset.csv` is available, or upload it when prompted.
3. Run all notebook cells in order.
4. The notebook generates `Nuclear_Technology_PowerBI_Ready.csv`.
5. Open the PBIX file in Power BI Desktop to explore the dashboard.

## Author

**Eric Rathod**  
Master of Artificial Intelligence student, Seneca Polytechnic  
[LinkedIn](https://www.linkedin.com/in/eric-rathod-aa335a310) · [GitHub](https://github.com/EricRathod)
