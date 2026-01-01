# Tax calculation app
This is a Python-based console application that helps users calculate their income tax under both the **Old** and **New** tax regimes. It allows deductions for the Old Regime, applies slab-wise tax calculations, includes a 4% cess, and recommends the more beneficial regime.

---

##  Features

- Accepts **Annual Salary** and **Deductions**
- Calculates:
  - Taxable Income under Old Regime
  - Slab-wise tax breakdown for both regimes
  - 4% health and education cess
  - Final tax liability and take-home salary
- Suggests the **better regime** based on net savings
- Validates inputs (no negatives)
- Allows **multiple calculations** in one session

---

##  Tax Rules

### Old Regime Slabs (Deductions Allowed)

| Income Slab (INR)        | Tax Rate |
|--------------------------|----------|
| 0 – 2,50,000             | 0%       |
| 2,50,001 – 5,00,000      | 5%       |
| 5,00,001 – 10,00,000     | 20%      |
| Above 10,00,000          | 30%      |

 *Deductions (e.g., 80C, HRA, PF) are applicable*

---

### New Regime Slabs (No Deductions Allowed)

| Income Slab (INR)        | Tax Rate |
|--------------------------|----------|
| 0 – 2,50,000             | 0%       |
| 2,50,001 – 5,00,000      | 5%       |
| 5,00,001 – 7,50,000      | 10%      |
| 7,50,001 – 10,00,000     | 15%      |
| 10,00,001 – 12,50,000    | 20%      |
| 12,50,001 – 15,00,000    | 25%      |
| Above 15,00,000          | 30%      |

 *No deductions allowed*

 *4% cess is added to the total tax in both regimes*



##  How to Run

1. Ensure Python 3 is installed.
2. Run the script:
   ```bash
   python Tax_calculation_app.ipynb
(or download and open it via Jupyter Notebook to easily run the file)

Thankyou

Hello
