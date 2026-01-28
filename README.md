# Roof Maxx Market Analytics

Comprehensive Python toolkit for market research, predictive analytics, and sales intelligence for the roof treatment industry.

## Features

- **Market Research**: Demographic data collection and analysis
- **Predictive Analytics**: ML models for market penetration and sales forecasting
- **Geospatial Analysis**: Interactive maps and territory optimization
- **Customer Segmentation**: RFM analysis and CLV calculations
- **Sales Dashboard**: Interactive Streamlit application

## Setup

### Prerequisites
- Python 3.11+
- UV package manager

### Installation
```bash
# Install UV if you don't have it
curl -LsSf https://astral.sh/uv/install.sh | sh

# Create virtual environment
cd envs/roof_maxx_analytics
uv venv
uv sync
source .venv/bin/activate

# Return to project root
cd ../..
```

### Running the Dashboard
```bash
# Activate environment
source activate_project.sh roof

# Run Streamlit app
cd projects/roof_maxx_analytics
streamlit run app/streamlit_dashboard.py
```

### Running Analysis in Jupyter
```bash
# Activate environment
source activate_project.sh roof

# Start Jupyter
jupyter notebook
```

## Project Structure
```
roof-maxx-analytics/
├── envs/
│   └── roof_maxx_analytics/
│       ├── pyproject.toml
│       ├── uv.lock
│       └── .venv/
├── projects/
│   └── roof_maxx_analytics/
│       ├── app/
│       │   └── streamlit_dashboard.py
│       ├── src/
│       │   └── market_analysis.py
│       ├── notebooks/
│       └── data/
└── activate_project.sh
```

## Technologies

- Python 3.11+
- Pandas, NumPy - Data manipulation
- Scikit-learn - Machine learning
- Plotly, Matplotlib, Seaborn - Visualization
- Folium, GeoPandas - Geospatial analysis
- Streamlit - Interactive dashboard