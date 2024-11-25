# Energy-Planning-Italy
Strategic roadmap for Italy’s power sector using Calliope, Gurobi, and QGIS

## 🛠 Tools and Technologies
- **Calliope**: Energy system modeling framework.
- **Gurobi**: Optimization solver for energy models.
- **QGIS**: GIS-based analysis for geospatial data.

## 📊 Project Features
- Scenario-based modeling of Italy's power sector.
- Analysis of CO₂ emissions, energy costs, and technology investments.
- GIS visualizations of energy production and consumption.

## 📂 Project Structure
- `data/`: Raw and processed datasets.
- `models/`: Calliope and Gurobi model files.
- `results/`: Generated outputs such as charts and maps.
- `docs/`: Reports and presentations.

## 🌍 Modelling Scenarios
- Base case, the italian energy sector situation in 2023 without any modification
- 2030 case, a suggestion on how to comply to the “fit for 55 plan”
- 2050 case, in which Italy reaches carbon neutrality in 2050
- Potential off-shore wind farms in Italy; a study on how the current energy mix would change with the hypothetical instant installation of off-shore wind farms

## ⚖️ Modelling Approach:
- Energy System Model: Calliope
- Operation Mode, used when analyzing current (or hypothetical current) energy mix
- Planning Mode, used when suggesting pathways to reach certain policies
- Optimization: Least costly Solution
- No unmet demand

## Energy Systems Modelling Limitations
- Modeler's approach may lead to forced solutions, and not unbiased ones.
- Not every important factor can be evaluated mathematically. (e.g., Public opinion, Job employment,…)
- Calliope optimizes based on the final demands and does not consider the process and the years in between.
- Optimized solution is just one point in decision space. This single solution is based on a plethora of hypothesis, and many uncertainties are involved. Generating “Near-Optimal Solutions” can help us with that.

## Other Contributors
- Lorenzo Rossi
- Alessandro Mastena

## 📄 References
- Calliope: https://calliope.readthedocs.io/en/stable/
- Gurobi: https://www.gurobi.com
