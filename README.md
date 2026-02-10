# FEMA Disaster Processing Analysis

## Double Time: Tracking FEMA's Processing Speed Bump

An interactive data visualization exploring the relationship between FEMA budget cuts, staff reductions, and disaster declaration processing delays in 2024-2025.

### Overview

This project analyzes FEMA disaster declaration processing times across all U.S. states and territories, revealing a dramatic increase in processing delays following budget cuts and staff reductions in 2025. The visualization tracks how policy changes directly correlate with longer wait times for disaster assistance.

### Key Finding

Disaster declaration processing times **doubled in the fourth quarter of 2025** following significant budget cuts and staff reductions at FEMA. According to systems analysts, fewer people processing the same volume of applications creates bottlenecks that cascade through the system—delays that compound during the exact periods when disaster victims need help most.

### Data & Methodology

- **Data Source**: FEMA disaster declarations (292 records)
- **Analysis Period**: Historical disaster data through Q4 2025
- **Smoothing Method**: LOESS regression for trend estimation
- **Confidence Intervals**: 95% CI bands showing uncertainty bounds

### Files

- `FemaFinal.html` - Interactive visualization (open in browser)
- `FemaFinal.ipynb` - Jupyter notebook with full analysis
- `Fema_Data.csv` - Raw FEMA disaster data
- `FEMA.mp4` - Hero video background

### How to Use

1. Open `FemaFinal.html` in your web browser to view the interactive visualization
2. Hover over data points to see individual disaster details
3. Interactive chart elements include:
   - Disaster data points (green dots)
   - Smoothed trend line (purple)
   - 95% confidence intervals (shaded area)
   - Key policy events marked with diamonds

### Key Events Marked

**2024 (Blue diamonds):**
- March: DHS Appropriations Act adds $20.261 billion for Disaster Relief Fund
- June: Congress passed $500 million flood mitigation fund

**2025 (Red diamonds):**
- May: Staff reduced by 1/3, $646M budget cut
- October: FEMA canceled $11B in disaster payments

### Author

Dagmar Rothschild

### Source

Data and analysis exploring the impact of policy decisions on FEMA's operational capacity and disaster response times.
