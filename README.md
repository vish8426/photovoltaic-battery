# photovoltaic-battery
Power Electronics &amp; Applications - Photovoltaic Battery Integrated Electrical System

## About
- Power source is the PV panel with a nominal power rating of 260W. 
- A PV-battery charger converts the solar power to supply DC link, which is rated to be 48V DC.  
- The battery bank is rated as 48V nominal and 4.8kWH in capacity.  
- A DC to single-phase AC converter supplies AC loads, which is rated as 230V (RMS) and 50Hz.  

## Table of Contents

- [Overview](#overview)
- [System Specifications](#system-specifications)
- [System Architecture](#system-architecture)
- [Methodology](#methodology)
- [Simulation Files](#simulation-files)
- [Applications](#applications)
- [License](#license)

## Overview

The system integrates a 260W photovoltaic panel with a 4.8kWh battery bank through a PV-battery charger, supplying a 48V DC link. A DC to single-phase AC converter then provides power to AC loads. This setup is simulated using MATLAB/Simulink to analyze performance and efficiency.

## System Specifications

- **Photovoltaic Panel**: 260W nominal power rating.
- **Battery Bank**: 48V nominal voltage, 4.8kWh capacity.
- **DC Link**: 48V DC supplied by the PV-battery charger.
- **AC Output**: Single-phase AC power supplied to loads via a DC-AC converter.

## System Architecture

The system comprises the following components:

- **PV Panel**: Captures solar energy and converts it into electrical power.
- **PV-Battery Charger**: Regulates the charging of the battery bank from the PV panel.
- **Battery Bank**: Stores energy for use during periods of low solar irradiance.
- **DC-AC Converter**: Converts DC power from the battery bank to single-phase AC power for load consumption.

## Methodology

1. **Modeling**: Develop Simulink models for each component, including the PV panel, battery charger, battery bank, and DC-AC converter.
2. **Simulation**: Perform simulations to analyze the behavior of the integrated system under various operating conditions.
3. **Analysis**: Evaluate system performance metrics such as efficiency, voltage regulation, and load handling capabilities.

## Simulation Files

- `Final_Project_Arrangement.slx`: Complete system simulation model.
- `PV_and_Inverter.slx`: Simulation model focusing on the PV panel and inverter.
- `Transformer_Part_1.slx`: Simulation model of the transformer component.
- `Power Electronics & Applications PV System Project Report Compiled.pdf`: Comprehensive project report detailing system design and analysis.

## Applications

- **Residential Energy Systems**: Provide reliable and sustainable power solutions for homes.
- **Remote and Off-Grid Areas**: Supply electricity in locations without access to the main power grid.
- **Educational Purposes**: Serve as a learning tool for students and researchers in renewable energy and power electronics.

## License

This project is licensed under the [MIT License](LICENSE), allowing for open collaboration and modification.
