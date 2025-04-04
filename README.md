# Project Data Archive

This repository contains **two ZIP archives** with simulation results and outputs from a numerical methods project studying wind and solar investment decisions under various policy scenarios.

- One ZIP file contains results using the **full original dataset** (`Numerical_Methods_PPA.zip`).
- The other ZIP contains results where **plants with capacity greater than 50 MW are split** into multiple smaller units for analysis (`Numerical_Methods_PPA_Split.zip`).

Each ZIP archive is structured by policy scenario and includes both **figures** and **tables** to allow easy exploration and comparison.

---

## 📦 ZIP Folder Structure

Each `.zip` file follows this structure:


## 📁 Folder Details

### 🔹 `Baseline/`

#### 📊 Figures

- `01_supply_function_cpr_theta_2500`  
  Supply function under counterparty risk with θ = 2500.

- `02_supply_function_cpr_theta_3500`  
  Supply function under counterparty risk with θ = 3500.

- `03_supply_function_cpr_theta_4500`  
  Supply function under counterparty risk with θ = 4500.

- `04_equilibrium_price_vs_gamma_theta`  
  Equilibrium contract price as a function of γ and θ.

- `05_equilibrium_quantity_vs_gamma_theta`  
  Investment quantity at equilibrium under different γ and θ.

- `06_welfare_vs_gamma_theta`  
  Total welfare across varying levels of γ and θ.

- `07_profit_vs_gamma_theta`  
  Profit in levels.

#### 📄 Tables

- `01_wind_solar_projects_cpr_theta.xlsx`  
  Project-level data for the baseline scenario including technical and economic variables.

---

### 🔹 `Public_Guarantees/`

#### 📊 Figures

- `01_equilibrium_price_vs_gamma_theta_publicg`  
  Contract price under public guarantee scenario across γ and θ.

- `02_equilibrium_quantity_vs_gamma_theta_publicg`  
  Investment quantity under public guarantees for various γ and θ.

- `03_welfare_vs_gamma_theta_publicg`  
  Welfare outcomes under public guarantees.

- `04_profit_share_vs_gamma_theta_publicg`  
  Profit shares (%).

#### 📄 Tables

- `01_wind_solar_projects_cpr_theta_with_public-g.xlsx`  
  Data for each project under the public guarantees scenario.

---

### 🔹 `Public_Subsidies/`

#### 📊 Figures

- `01_supply_function_cpr_T_0.2_theta_3500`  
  Supply function under public subsidies with \( T = 0.2 \), θ = 3500.

- `02_supply_function_cpr_T_0.4_theta_3500`  
  Supply function under public subsidies with \( T = 0.4 \), θ = 3500.

- `03_supply_function_cpr_T_0.6_theta_3500`  
  Supply function under public subsidies with \( T = 0.6 \), θ = 3500.

- `04_supply_function_cpr_T_0.8_theta_3500`  
  Supply function under public subsidies with \( T = 0.8 \), θ = 3500.

- `06_equilibrium_price_vs_gamma_T`  
  Contract price trends under subsidies, varying γ and T.

- `07_equilibrium_quantity_vs_gamma_T`  
  Investment quantity under public subsidies, by γ and T.

- `08_equilibrium_welfare_vs_gamma_T`  
  Welfare outcomes across γ and T under subsidy support.

- `09_profit_share_vs_gamma_T`  
  Profit shares (%).

- `10_welfare_ratios_public_g_t`  
  Welfare comparison: public guarantees vs subsidies.

#### 📄 Tables

- `01_wind_solar_projects_cpr_T_theta_3500.xlsx`  
  Project-level data under the public subsidy `T` scheme for θ = 3500.
- `02_wind_solar_projects_cpr_public_expenditure_T_G`
  
  Project-level data under the condition of public expenditure with G = public expenditure with T.
---

## 🔖 Notes

- All figures are in `.pdf` format and numbered for logical ordering.
- All tables are in `.xlsx` format and contain raw or processed model output.
- File naming is consistent across scenarios to simplify comparison.
- Scenarios:
  - **Baseline:** No intervention
  - **Public_Guarantees:** Scenario with public guarantees
  - **Public_Subsidies:** Scenario with public subsidies `T`
