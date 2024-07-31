# Data Science for Fixed Income


This is an Academic project Postgraduate in Data Science made in collaboration with my colleagues below:

- https://github.com/Przon | [Fernando Reis]
- https://github.com/lfbr0 | [Luis Ribeiro]
- https://github.com/renato747 | [Renato Morais]

## Study Case I

### Overview
This is a group project from Data Science Pos Degree which consists in analyzing a government Capital Indexed Inflation Linked Bond (ILB) with specific details, using statistical models for simulation and risk assessment.


### Paramenters used:

- Notional Amount: 25,000 USD
- Coupon Type: Fixed
- Coupon Rate: 6.75%
- Coupon Frequency: Semi-annual
- Currency: USD
- Issue Date: 31/07/2020
- Maturity Date: 21/07/2025
- Trade Date: 18/09/2020
- Settlement Lag: T+1
- Day Count: ACT/ACT
- Inflation Reference Index: US Consumer Price Index
- Inflation Reference Index Level at Issue: 237.14365
- Inflation Reference Index Level at Settlement: 251.14721
- Inflation Model: Geometric Brownian Motion
- Model Parameters: 𝜇^ = 0.05321, σ^ = 0.06358
- Yield Curve Parameters (Nelson–Siegel-Svensson): 𝛽0 = 5.9%, 𝛽1 = −1.6%, 𝛽2 = −0.5%, 𝛽3 = 1%, 𝜏1 = 5, 𝜏2 = 0.5


### Tasks:

1. Compute the accrued interest.
2. Simulate 10,000 scenarios for the inflation rate curve and CPI index.
3. Calculate the ILB cash flows and estimate their fair value for each scenario.
4. Estimate and analyze the ILB price distribution, including interest rate and inflation risk measures.


## Study Case II

### Goal
Analyze a 25-year fixed rate receiver interest rate swap (IRS) contract using Bloomberg information and EUR yield curve data, employing interpolation techniques and risk assessment.

### Paramenters used:

- Issue Date: 19/01/2007
- Floating Rate: EURIBOR 6 months
- Valuation Date: 14/04/2019
- Bloomberg EUR Yield Curve (14/04/2019):
- Rates ranging from -0.364% to 1.152% for maturities from 2019 to 2069.


### Tasks:

1. Build the complete yield curve using interpolation techniques.
2. Compute the accrued interest in the fixed and floating legs of the contract.
3. Calculate the clean (principal) and dirty (total) market value of the swap contract.
4. Estimate the net present value of the contract.
5. Estimate the swap par rate.
6. Estimate the following IRS Greeks: PV01, DV01, Gamma, and discuss the interest rate risk of the contract.
