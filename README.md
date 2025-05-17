# Turbomachinery-Student-Project-Pump-Analysis-DHBW-Karlsruhe-#743
# Pump Analysis – Turbomachinery Student Project (DHBW Karlsruhe)

This project analyzes the operating behavior of a water pump based on real-world measurement data and manufacturer specifications. The analysis was conducted as part of the Turbomachinery course at DHBW Karlsruhe.

## Project Description

The pump under investigation is used in an industrial environment. Over the course of one full day (1440 minutes), volumetric flow rate data was recorded after the pump. This data serves as the basis for evaluating the pump’s energy usage and overall efficiency.

The manufacturer’s hydraulic performance curves were used to interpolate relevant parameters such as:
- Hydraulic head
- Hydraulic efficiency

The impeller diameter is specified as 264 mm.

## Objectives and Implemented Features

The following key tasks were addressed in this project:

1. Calculate the Energy Consumption  
   - Total electrical input energy over 24 hours  
   - Derived from interpolated hydraulic power and efficiency

2. Determine Average Pump Efficiency  
   - Hydraulic efficiency interpolated based on flow rate  
   - Daily average calculated via ratio of total hydraulic to electric power

3. Calculate Unused Energy  
   - Determined the total non-hydraulic (lost) energy  
   - Based on difference between input and hydraulic energy

4. Additional Visualizations (Optional)  
   - Electrical power over time  
   - Efficiency over time with average reference line  
   - Instantaneous and cumulative loss energy  
   - All plots were created using matplotlib

## Tools Used

- Language: Python 3.x
- Environment: Jupyter Notebook
- Libraries:
  - pandas, numpy, matplotlib
  - scipy.interpolate (for linear interpolation)

## Submission

The project fulfills the requirements defined in the course description:

- All tasks are implemented in the notebook
- Results are visualized and interpreted
- This README provides a clear project overview

## Author

#743  
DHBW Karlsruhe  
Faculty of Mechanical Engineering  
Course: Turbomachinery



