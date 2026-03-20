# Correlations_fitting

A Jupyter notebook for plotting and fitting correlation data between energy levels and voltage losses in organic solar cells.

## Files

| File | Description |
|------|-------------|
| `Correlation_Plot_Fit.ipynb` | Main notebook containing plotting and fitting functions |

## Main Function

**`plot_deltaE_vs_deltaVrad(csv_path)`**

Reads a CSV file with columns `E_CT-S1`, `Delta_V_rad`, and `Name`, then:
- Plots scatter points for each data point
- Performs linear fit (y = mx + b)
- Adds text labels for each point
- Draws horizontal reference line at y = 0.005
- Marks intersection point of fit line with reference line

## Dependencies

- numpy
- pandas
- matplotlib

## Author

mzjswjz
