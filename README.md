# County Rainfall and Planting Advisory

**Name:** Amanda Ireri
**Cohort:** 1 Million Devs

## Project summary

A farmer-support NGO sends SMS planting advice in five counties (Nairobi, Nakuru, Kisumu, Mombasa and Machakos). This project cleans one hand-typed station record (Machakos), uses NumPy to analyse monthly rainfall, and produces a planting advisory for each county. Results are saved in `rainfall_summary.csv`.

## How to run

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AmandaIreri/plp-da-a2-rainfall-advisory/blob/main/rainfall_analysis.ipynb)

Click the badge, then choose **Runtime → Run all**. Install the requirements with `pip install -r requirements.txt` if you run it locally.

## Planting advisory

- Plant in April to May in Nairobi, Nakuru, Kisumu and Mombasa, the two-month stretch with the most rain (265 to 420 mm).
- Plant in November to December in Machakos (278 mm), the driest county with 811 mm a year and 6 dry months.
- Two Machakos readings were missing and replaced with the average (68 mm), so Machakos results are less certain than the other counties.
