# Housing Analysis: Rent vs Buy Decision in High-Interest Rate Environment

## Overview

This project explores the financial implications of renting versus buying a home, particularly in an environment of high interest rates. The analysis focuses on comparing monthly costs for renting a home versus purchasing one, factoring in home prices and mortgage rates over time.

## Key Components

### Data Collection:
The data used in this analysis includes:
- Historical home prices over time.
- Mortgage rates (specifically the 30-year fixed mortgage rate).
- Both datasets were merged to allow for a side-by-side comparison of trends.

### Visualization:
- A two-y-axis plot was created to visualize both home prices and mortgage rates over time.
  - Home price trends are plotted on the primary y-axis (blue line).
  - Mortgage rates are plotted on the secondary y-axis (red line).
- This helped in understanding how mortgage rates, which have a direct impact on buying costs, fluctuate with the housing market.

### Rent vs Buy Cost Analysis:

#### Monthly Mortgage Payment Calculation:
For the buy scenario, the monthly mortgage payment was calculated using:

Monthly Payment = P * r * (1 + r)^n / [(1 + r)^n - 1]

Where:
- `P` is the home price.
- `r` is the monthly interest rate (annual mortgage rate divided by 12).
- `n` is the number of payments (typically 30 years or 360 months).

This allowed for comparing the monthly costs of purchasing a home versus renting.

### Interest Rate Impact on Buying:
- The analysis revealed that as mortgage interest rates rise, the monthly payments for homebuyers increase significantly.
- In contrast, renters only experience rent increases tied to inflation or market conditions, which often grow at a slower rate compared to mortgage payments in a high-interest environment.

### Key Insight: Renting is Cheaper:
- Renting is financially more viable than buying when interest rates are high, especially for those who are not planning to stay in a home for more than 5-7 years. This is due to:
  - Lower monthly costs (rental payments).
  - Avoidance of high mortgage interest expenses, particularly in the early years of a mortgage, when interest constitutes the majority of the payment.
  - Flexibility in relocating without the burdens of homeownership.

### Other Considerations:
- While renting may be cheaper in the short term, homeownership has long-term financial benefits, such as building equity and potential tax advantages, which were also discussed.

## Conclusion

This analysis concludes that during periods of high interest rates, renting can often be the more financially prudent option for individuals who are uncertain about long-term homeownership or those seeking to minimize monthly expenses. This dynamic shifts when interest rates are low, making buying more advantageous due to lower mortgage costs.
