# Assignment 2

### Author: Viren Varma


---

## Selection of Macro-Economic Indicators

Visit [FRED](https://fred.stlouisfed.org/) and select three macro-economic indicators. You can use an R or Python package, for example, `quantmod` or `fredapi`, or utilize another package or FRED API calls.

### Explanation of Chosen Economic Indicators

1. **Labor Market Indicator:**  
   **Job Openings: Total Nonfarm (JOLTS):** The number of available job openings, reflecting employer demand for workers.

2. **Consumer Confidence Indicator:**  
   **Consumer Sentiment:** A measure of household confidence in the economy, influencing future spending behavior.

3. **Consumer Spending Indicator:**  
   **Retail Sales:** The total sales receipts of retail stores, indicating the level of consumer spending in the economy.

---

## Analysis of Trading Volume Time-Series and Patterns

### Do you see any patterns in the time-series? Is there any seasonality?

1. **Trade Volume for US Treasuries**  
   **Observation:** There is a notable peak and discernible patterns, but no obvious seasonality.  
   **Explanation:** Rather than seasonal impacts, the early 2020 spike most likely represents market reactions to the COVID-19 pandemic.

2. **Repo Primary Dealer**  
   **Observation:** There is a notable peak at the beginning of 2020, which is followed by a fall, but no discernible seasonality.  
   **Explanation:** The rise most likely has no recurrent seasonal trend and is related to the stress on the financial markets during the COVID-19 epidemic.

3. **Repo GCF Repo**  
   **Observation:** There is a downward trend after early 2020 with fluctuations, but no clear seasonality.  
   **Explanation:** The decline after the early 2020 spike likely reflects market adjustments post-pandemic onset, without recurring seasonal patterns.

4. **Repo Triparty Repo**  
   **Observation:** The series shows a general upward trend with significant volatility around 2020, including a sharp drop and rapid recovery.  
   **Explanation:** The volatility likely corresponds to the COVID-19 pandemic's impact on markets. No clear seasonality is evident.

5. **Equity Issuance**  
   **Observation:** The series has frequent spikes and drops, with a notable spike in mid-2020.  
   **Explanation:** The mid-2020 spike likely reflects companies capitalizing on post-COVID market recovery and investor optimism in the tech sector.

6. **Equity Trading Volume**  
   **Observation:** The series shows a slight overall upward trend with a major spike in Q1 2020, followed by a rapid decline within the same quarter.  
   **Explanation:** The Q1 2020 spike is likely due to the intense market volatility and trading activity during the onset of the COVID-19 pandemic, as investors reacted to the uncertainty and market disruptions.

7. **Fixed Income Trading Volume**  
   **Observation:** The series shows a significant spike in Q1 2020, with Treasury and Agency MBS dominating the trading volume. Other categories like Non-Agency MBS, Corporate Debt, and Municipal have relatively lower volumes.  
   **Explanation:** The spike in Q1 2020 reflects increased demand for safer assets like Treasury and Agency MBS during the COVID-19 pandemic, as investors sought security amid market uncertainty. The lower trading volumes in Non-Agency MBS, Corporate Debt, and Municipal securities suggest a flight to quality during this period.

8. **Structured Finance Trading Volume**  
   **Observation:** The series is steady with a spike in January 2021, driven mainly by ABS and Agency TBA volumes.  
   **Explanation:** The January 2021 spike likely reflects increased trading in ABS and Agency TBA due to favorable market conditions.

9. **Agency Trading Volume**  
   **Observation:** The series shows a positive trend leading up to a spike in Q1 2020, followed by a negative trend afterward.  
   **Explanation:** The Q1 2020 spike is likely due to heightened market activity during the early COVID-19 period, with the subsequent decline reflecting reduced trading as market conditions stabilized.

10. **Corporate Bond Trading Volume**  
   **Observation:** Trading volume spiked in March 2020 and January 2021, with an overall neutral to slightly negative trend.  
   **Explanation:** The spikes were due to market disruptions and adjustments, while the overall trend reflects stabilization or reduced activity after these peaks.

---

## Observations on Economic Indicators and Trading Volumes

1. **Treasury Trading Volume and GDP**  
   **Observation:** There are discernible surges in the volume of Treasury trade, especially at times of economic concern or major market events. There doesn't seem to be a discernible or reliable seasonal trend, though.  
   **Explanation:** Investors' flight to safety is seen in the surges in Treasury trading volume that frequently occur during times of economic stress or extreme volatility. Rather than following a dependable seasonal pattern, these movements may be influenced by significant economic data releases, geopolitical events, or policy changes.

2. **Equity Issuance and Unemployment**  
   **Observation:** There is typically a lack of seasonality in the issue of equity, with huge fluctuations. With regard to unemployment rates, there is no obvious negative relationship.  
   **Explanation:** The issuing of equity is subject to fluctuations in market conditions, investor sentiment, and business finance requirements. Companies may issue more equity during times of economic expansion or low unemployment, although this does not always correspond to unemployment rates.

3. **Equity Trading Volume, Unemployment, and Fed Funds Rate**  
   **Observation:** Equity trading volumes show high volatility with no apparent seasonal pattern. These volumes often spike during major market events or policy changes by the Federal Reserve.  
   **Explanation:** Equity trading volumes are sensitive to changes in market conditions, interest rate policies, and broader economic signals. The Fed Funds Rate influences investor behavior, often resulting in heightened trading activity during rate announcements or adjustments.

4. **Fixed Income Trading Volume and Economic Uncertainty**  
   **Observation:** Fixed income trading volume shows spikes, often aligning with periods of economic uncertainty or market turbulence, rather than seasonal patterns.  
   **Explanation:** Investors tend to move into fixed income securities during periods of uncertainty, which increases trading volumes. The lack of seasonality suggests that these movements are primarily event-driven rather than cyclical.

### Macro-Economic Relationships

1. **Unemployment:**  
   While they don't show much seasonality, they do react to more general economic patterns and events, like recessions and booms.

2. **Macro Indicator 2:**  
   Retail sales frequently exhibit seasonality, peaking during large sales occasions or holiday seasons, which is indicative of consumer purchasing patterns.

3. **Macro Indicator 3:**  
   Consumer Sentiment varies with the state of the economy, frequently falling in uncertain or downturning times. There is some seasonality; optimism is typically seen at the start of the year or at times when the economy is doing well.

---

## Observations on Cross-Market Trading Activity Correlations

1. **Treasury Trading Volume**  
   **Observation:** Treasury trading volume shows moderate to high positive correlations with other fixed income markets, such as repo markets and fixed trading volumes, but lower correlations with equity-related markets.  
   **Explanation:** Treasury trading activity is often driven by interest rate changes, economic uncertainty, and government policies, making it more closely tied to other fixed income securities. The lower correlation with equities reflects the contrasting nature of Treasuries as a safe-haven asset compared to riskier assets like stocks.

2. **Equity Issuance Volume**  
   **Observation:** Equity issuance volume exhibits low to moderate correlations with other trading volumes, indicating that its movement is not closely tied to other markets.  
   **Explanation:** Equity issuance is primarily influenced by company-specific factors, investor sentiment, and broader market conditions rather than direct market-to-market interactions. Companies tend to issue equity when market conditions are favorable, regardless of trading activities in other sectors.

3. **Equity Trading Volume**  
   **Observation:** Equity trading volume has moderate correlations with other trading volumes, particularly with structured finance and corporate bond trading, indicating some interconnectedness.  
   **Explanation:** Equity trading volumes are influenced by broader market liquidity, investor risk appetite, and economic conditions, which can spill over into other markets, such as corporate bonds and structured finance products. These correlations suggest that when investor confidence is high, it can boost activity across these related markets.

4. **Fixed Trading Volume**  
   **Observation:** Fixed trading volume is highly correlated with Treasury and other fixed-income-related markets, showing strong interconnectedness within the bond market.  
   **Explanation:** Fixed trading volumes reflect investor activity in bonds and other fixed-income securities, driven by changes in interest rates, economic data, and monetary policy. This inter-market correlation highlights the integrated nature of fixed-income markets, where movements in one sector often impact others.

5. **Structured Finance Trading**  
   **Observation:** Structured finance trading volume shows moderate correlations with equity and corporate bond markets, indicating a link between these credit-sensitive products.  
   **Explanation:** Structured finance products, such as asset-backed securities, are sensitive to credit conditions and investor risk tolerance. Their moderate correlations with equities and corporate bonds suggest that they are affected by broader credit market trends and investor sentiment.

6. **Agency Trading Volume**  
   **Observation:** Agency trading volume shows moderate correlations with Treasury and other fixed income markets, but lower correlations with equity-related markets.  
   **Explanation:** Agency securities, such as those issued by government-sponsored enterprises, are generally considered safe investments, closely tied to Treasuries. Their moderate correlation with other fixed income markets underscores their role as a lower-risk alternative within the broader bond market.

7. **Corporate Bond Trading Volume**  
   **Observation:** Corporate bond trading volume has moderate to high correlations with equity, structured finance, and fixed-income markets, highlighting its role as a bridge between credit and equity markets.  
   **Explanation:** Corporate bonds are influenced by both credit conditions and broader market risk sentiment, making them highly interconnected with other markets. When market conditions are favorable, corporate bonds often see increased trading alongside equities and other credit-sensitive securities.

   ---

   # Observations on Time-Series Patterns and Seasonality

1. **Treasury Issuance**  
   **Observation:** Treasury issuance has increased significantly over time, showing pronounced surges during times of economic strain or significant changes in policy.  
   **Explanation:** When the government raises borrowing to fund deficits and boost the economy, Treasury issuance frequently rises during economic downturns or fiscal stimulus initiatives. These peaks correspond to things like major government expenditure programs or financial crises.

2. **Treasury Outstanding**  
   **Observation:** The U.S. government's constant borrowing is reflected in the steadily rising total number of outstanding Treasury securities.  
   **Explanation:** Because the government must finance spending that exceeds revenue, budget deficits are the primary cause of the ongoing rise in the amount of outstanding Treasury debt. During periods of significant fiscal stimulus and economic downturns, the rate of increase quickens.

3. **Treasury Yield**  
   **Observation:** There is no discernible seasonality in Treasury yields, although they do show cyclical behavior with periods of rising and dropping rates.  
   **Explanation:** Monetary policy, inflation expectations, and general economic conditions all affect Treasury yields. The Federal Reserve's cycles of tightening and relaxing, combined with investor demand for safe-haven assets, are what determine yield swings.

4. **Mortgage Issuance**  
   **Observation:** There are cyclical trends in the issuance of mortgages, with notable increases during times of low interest rates and a favourable housing market.  
   **Explanation:** Mortgage issuance tends to increase when interest rates are low, making borrowing more attractive. Housing booms also lead to higher issuance, while economic downturns and tighter lending standards can reduce new issuance.

5. **Mortgage Outstanding**  
   **Observation:** Mortgage debt outstanding exhibits a long-term upward trend with occasional periods of slowdown or decline, particularly during economic downturns.  
   **Explanation:** The accumulation of mortgage debt is generally linked to housing market dynamics, consumer borrowing trends, and interest rate levels. Economic recessions can lead to a decline in outstanding mortgage levels due to defaults, paydowns, or reduced new borrowing.

6. **ABS Issuance**  
   **Observation:** The issue of asset-backed securities (ABS) varies greatly, clearly peaking during economic expansions and contracting during downturns.  
   **Explanation:** The issue of ABS is directly related to consumer credit requirements, including credit cards, vehicle loans, and other securitized assets. ABS issuance volumes are influenced by interest rates, the state of the economy, and market confidence.

7. **ABS Outstanding**  
   **Observation:** The outstanding volume of ABS shows a steady increase with periods of stagnation or decline during economic slowdowns.  
   **Explanation:** ABS outstanding grows when issuance is high and economic conditions are stable. During economic stress, such as the financial crisis, the volume may plateau or decline due to lower new issuance and increased repayment or defaults.

8. **Fixed Income Issuance**  
   **Observation:** The issue of fixed income securities exhibits a generally rising trend with sporadic spikes, signifying higher activity under certain economic circumstances.  
   **Explanation:** When market conditions are favorable, including in low-interest-rate environments or when businesses seek to raise capital, fixed income issuance tends to rise across many sectors, including corporate bonds and government securities. Due to enterprises' lock-in capital during market access periods, economic uncertainty can also be the driving force behind issuance.

   ---

# Relationship Between Macroeconomic Indicators and Financial Markets (2012-2021)

1. **Job Openings: Total Nonfarm (JOLTS)**  
   - **Treasury Issuance:** Higher job openings often align with increased Treasury issuance, indicating a link between labor market strength and government borrowing needs.  
   - **Treasury Outstanding:** Fluctuations in Treasury Outstanding are less consistent with JOLTS, suggesting short-term labor changes don't significantly impact overall debt levels.  
   - **Treasury Yield:** Little correlation exists, implying Treasury yields are driven by broader economic and monetary factors rather than labor market conditions.  
   - **Mortgage Issuance:** Increased job openings moderately correlate with higher mortgage issuance, reflecting boosted consumer confidence and home-buying activity.  
   - **Mortgage Outstanding:** Similar to issuance, higher JOLTS align with increased mortgage borrowing, supported by a stronger labor market.  
   - **ABS Issuance & Outstanding:** There's a noticeable correlation, with better job markets driving higher ABS issuance, likely due to increased consumer credit.  
   - **Fixed Income Issuance & Outstanding:** The relationship is mixed, indicating other factors like interest rates or corporate earnings have more influence.

2. **Consumer Sentiment**  
   - **Treasury Issuance:** Positive sentiment may reduce Treasury issuance needs, while lower sentiment can lead to increased government borrowing to support the economy.  
   - **Treasury Outstanding:** Less sensitive to consumer sentiment changes, showing overall debt levels remain stable despite mood shifts.  
   - **Treasury Yield:** Minimal correlation, suggesting yields are more affected by inflation expectations and Federal Reserve policies.  
   - **Mortgage Issuance:** Strong positive sentiment generally boosts mortgage issuance, as confident consumers are more likely to buy homes.  
   - **Mortgage Outstanding:** Higher sentiment supports increased mortgage borrowing, maintaining activity in the housing sector.  
   - **ABS Issuance & Outstanding:** Better sentiment tends to drive higher ABS issuance and outstanding levels, reflecting increased consumer borrowing.  
   - **Fixed Income Issuance & Outstanding:** Mixed relationships indicate broader factors influence fixed income markets beyond just consumer sentiment.

3. **Retail Sales**  
   - **Treasury Issuance:** Weak correlation, implying retail sales don't significantly impact government borrowing needs.  
   - **Treasury Outstanding:** Little to no correlation, indicating overall debt levels aren’t directly influenced by retail activity.  
   - **Treasury Yield:** No strong relationship, as yields are more influenced by factors like inflation and central bank policies.  
   - **Mortgage Issuance:** Moderate correlation, with strong retail sales signaling a healthy economy that supports more home buying and mortgage borrowing.  
   - **Mortgage Outstanding:** Similar to issuance, sustained retail activity supports ongoing mortgage borrowing.  
   - **ABS Issuance & Outstanding:** Mixed correlations suggest retail sales influence consumer credit and ABS markets, but other factors also play roles.  
   - **Fixed Income Issuance & Outstanding:** No strong or consistent correlation, indicating these markets are driven by broader economic and financial factors.

   ---
# Observations and Analysis on Various Financial Metrics

1. **Treasury Issuance Correlations**  
   **Observations:** Moderately correlated with Treasury outstanding and fixed income issuance; weaker with mortgages.  
   **Potential Explanation:** Treasury issuance aligns with overall debt markets, while mortgages are more housing-driven.

2. **Treasury Outstanding Correlations**  
   **Observations:** Strong correlation with Treasury issuance and fixed income outstanding; moderate with mortgages and ABS.  
   **Potential Explanation:** Government borrowing increases outstanding Treasuries, influencing broader debt markets.

3. **Treasury Yield Correlations**  
   **Observations:** Yields typically inversely correlate with issuance; influenced by macroeconomic factors.  
   **Potential Explanation:** Yields respond to inflation and policy more than directly to issuance volumes.

4. **Mortgage Issuance Correlations**  
   **Observations:** Moderately correlated with mortgage outstanding, ABS issuance, and fixed income issuance.  
   **Potential Explanation:** Mortgage issuance reflects housing demand, aligning with other credit markets.

5. **Mortgage Outstanding Correlations**  
   **Observations:** Strong correlation with mortgage issuance; moderate with ABS outstanding.  
   **Potential Explanation:** Mortgage balances grow with issuance, often tied to ABS markets.

6. **ABS Issuance Correlations**  
   **Observations:** Strongly correlated with ABS outstanding; moderate with mortgage issuance.  
   **Potential Explanation:** ABS issuance is directly linked to outstanding volumes, often backed by mortgages.

7. **ABS Outstanding Correlations**  
   **Observation:** Strong correlation with ABS issuance; moderate with mortgage metrics.  
   **Explanation:** ABS markets closely track issuance, especially for mortgage-backed securities.

8. **Fixed Income Issuance Correlations**  
   **Observation:** Strong correlation with fixed income outstanding; moderate with Treasury and mortgage issuances.  
   **Explanation:** Fixed income issuance influences overall debt markets, reflecting broader economic conditions.

   ---
# Observations

1. **US Marketable Treasury Issuance, Outstanding, and Interest Rates**  
   - **Observation:** Treasury issuance and outstanding have shown a consistent upward trend, with notable spikes in issuance during periods of economic stress (e.g., financial crises). Interest rates influence issuance volumes but are not shown in the plot.  
   - **Explanation:** The government increases borrowing during economic stress to address fiscal needs, which drives up Treasury issuance. Although interest rates impact issuance volumes, their effect is not always directly visible in the issuance plots.

2. **US MBS Issuance and Outstanding**  
   - **Observation:** Mortgage-Backed Securities (MBS) issuance and outstanding have grown steadily, with periodic surges, particularly during periods of lower interest rates that encourage refinancing and home purchases.  
   - **Explanation:** Lower interest rates make refinancing and home purchases more attractive, leading to increased MBS issuance and outstanding volumes.

3. **US ABS Issuance and Outstanding**  
   - **Observation:** Asset-Backed Securities (ABS) issuance spiked around the financial crisis and has since seen fluctuations. Outstanding volumes are more stable, reflecting the long-term nature of the underlying assets.  
   - **Explanation:** The financial crisis prompted a surge in ABS issuance, but since then, issuance has been more variable. Outstanding ABS volumes remain stable due to the long-term nature of these securities.

4. **US Fixed Income Issuance and Outstanding**  
   - **Observation:** Fixed income issuance and outstanding have grown consistently, with issuance spikes in response to economic events, indicating increased borrowing needs during such times.  
   - **Explanation:** Economic events often lead to increased borrowing needs, causing spikes in fixed income issuance. The consistent growth in outstanding volumes reflects ongoing demand for fixed income securities.

5. **US ABCP and CP Outstanding**  
   - **Observation:** Asset-Backed Commercial Paper (ABCP) and Commercial Paper (CP) outstanding show sharp declines during crises, particularly evident during the 2008 financial crisis, followed by a more gradual recovery.  
   - **Explanation:** Financial crises lead to reduced confidence and liquidity in commercial paper markets, causing significant declines in outstanding volumes. Recovery is gradual as market conditions stabilize.

6. **US Municipal Issuance**  
   - **Observation:** Municipal issuance has been volatile, with peaks in issuance often correlating with periods of fiscal stimulus or infrastructure spending initiatives.  
   - **Explanation:** Volatility in municipal issuance is linked to varying fiscal and infrastructure spending needs, which drive peaks in issuance during times of increased investment or fiscal stimulus.

7. **US Corporate Bond Issuance**  
   - **Observation:** Corporate bond issuance has steadily increased, with significant spikes during low-interest-rate periods, allowing corporations to refinance debt or raise capital cheaply.  
   - **Explanation:** Corporations take advantage of low-interest rates to issue bonds at favorable terms, leading to spikes in issuance. The overall trend reflects increased corporate borrowing needs and refinancing activity.
   
