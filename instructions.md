# Portfolio Rebalancing Calculator — Instructions

## What Is This Calculator?

The Portfolio Rebalancing Calculator helps you align your investments with a target
factor exposure. You define target Fama-French factor loadings and a geographic
allocation, then enter your current holdings. The calculator tells you exactly how
much to buy or sell in each fund to match your targets.

---

## Step 1 — Configure Funds

Open the **Funds** tab to manage the universe of ETFs and mutual funds the
calculator can use.

- Each fund row shows its ticker, name, factor loadings, and geographic split.
- Toggle the checkbox on the left to include or exclude a fund from rebalancing.
- Click **Add Fund** to add a custom fund by ticker, then fill in its factor
  exposures and geographic weights manually.
- Factor loadings must be accurate for the optimization to work well — use
  published fund factor data where possible.
- Geographic weights (US / International / Emerging) must sum to 100% per fund.

---

## Step 2 — Enter Your Holdings

Switch to the **Portfolio** tab. The Holdings section at the top shows your
current positions.

- Click the **+** button or use the Add Holding dropdown to add a position.
- Enter the current market value (in your local currency) for each holding.
- Remove a holding with the trash icon on its row.
- The **Total Value** shown is the sum of all your holdings and drives all
  rebalancing calculations.

---

## Step 3 — Set Your Target Allocation

Below your holdings you will find two target sections.

- **Factor Targets:** set the desired loading for each Fama-French factor
  (Mkt-RF, SMB, HML, RMW, CMA). Hover over a factor name for a plain-English
  description.
- **Geographic Breakdown:** set the percentage you want in US, International,
  and Emerging markets. These three values must add up to 100%.
- The calculator will not run until the geographic weights are valid (shown in
  green when correct).

---

## Step 4 — Read the Rebalance Results

Once your holdings and targets are valid, the **Rebalance Forward** section
appears automatically on the Portfolio tab.

- Each fund row shows the current value, the target value, and the difference
  (positive means buy, negative means sell).
- The **Current vs Target Factor** table compares your portfolio's actual factor
  loadings against your targets.
- The **Geographic Breakdown** table shows current vs target allocation across
  US, International, and Emerging.
- Small residuals are normal due to the discrete nature of available funds.

---

## Understanding the Fama-French Factors

**Mkt-RF (Market Factor)**
Exposure to broad equity market returns above the risk-free rate. A loading of
1.0 means the portfolio moves in line with the overall market.

**SMB (Small Minus Big)**
Tilt toward small-cap stocks. A positive value means more exposure to small
companies, which have historically earned a size premium.

**HML (High Minus Low)**
Tilt toward value stocks (high book-to-market ratio). A positive value means
more exposure to cheap, value-oriented companies.

**RMW (Robust Minus Weak)**
Tilt toward profitable companies. A positive value means more exposure to firms
with robust operating profitability.

**CMA (Conservative Minus Aggressive)**
Tilt toward companies that invest conservatively. A positive value means more
exposure to firms with low asset growth.

---

## Tips & Troubleshooting

- If **Rebalance Forward** is missing, check that geographic targets sum to 100%
  and that at least one fund is selected in the Funds tab.
- If a fund appears in an error banner, open the Funds tab and correct its
  geographic or factor values.
- Adding more funds gives the optimizer more flexibility to match your factor
  targets precisely.
- Your data is stored locally in the browser — nothing is sent to any server.
  Refreshing the page will reset all inputs.
