### Tata-fleet-intelligence-suite ###
AI-powered Fleet Intelligence Suite for Tata Steel West Bokaro to reduce HEMM idle time through analytics, simulation, predictive maintenance, and operator insights.

This application helps Tata Steel West Bokaro's shift supervisors and managers reduce idle time in dumpers, shovels, and other mining equipment. Built as an intern project with limited data and no real-time API access, it transforms monthly FMS exports into actionable insights.

## 📊 Key Features

- **Analytics Dashboard** – Identify problem equipment, shifts, and time windows with interactive Pareto charts and heatmaps
- **Simulation Engine** – Test dispatch strategies (Nearest-First, Shortest-Queue, Mixed) without disrupting real operations
- **Predictive Maintenance** – Flag equipment at risk of failure with risk scoring and maintenance calendar recommendations
- **Operator Insights** – Rank operator performance and identify coaching opportunities
- **Full System Report** – Generate comprehensive PDF/Excel reports for management meetings

## 🎯 Business Impact

- Reduce HEMM idle time by 15-30% through data-driven SOP changes
- Schedule proactive maintenance based on failure risk patterns
- Coach underperforming operators with specific behavioral recommendations
- Provide management with clear ROI calculations

## 🛠️ Tech Stack

- **Frontend/Backend**: Streamlit (Python)
- **Data Processing**: Pandas, Polars
- **ML Framework**: Scikit-learn (Random Forest)
- **Visualization**: Plotly
- **Simulation**: SimPy
- **Report Generation**: reportlab, openpyxl
