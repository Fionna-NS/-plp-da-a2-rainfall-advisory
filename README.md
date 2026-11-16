# Rainfall Planting Advisory

Analysis of monthly rainfall for five Kenyan counties (Nairobi, Nakuru, Kisumu, Mombasa, Machakos) to support an NGO's SMS planting advice. The raw Machakos data contained invalid entries, which are cleaned and imputed, and NumPy is used for all calculations.

## How to run
1. `pip install -r requirements.txt`
2. Open `rainfall_analysis.ipynb` in Jupyter or Colab.
3. Choose Restart Kernel and Run All. This regenerates `rainfall_summary.csv`.

## Planting advisory
- Nairobi, Nakuru, Kisumu and Mombasa should plant in April–May, at the start of the long rains.
- Machakos should plant in November–December and favour drought-tolerant crops, since it has six dry months.
- Machakos has two imputed months (April and September), so its totals are estimates and advice there should be confirmed with a seasonal forecast.
