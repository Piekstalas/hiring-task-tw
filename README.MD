# Liquidity Provider Analysis
## Summary
This analysis examines transaction success rates across different liquidity provider platforms. We found that success rates vary significantly between platforms, ranging from 29.4% to 37.1%.

If all platforms improved their success rates by just 1p.p. (percentage point), we could capture an additional **\$6.0M** in monthly transaction volume. With an average fee of 2.5%, this represents **\$150k** in additional monthly revenue - or **\$1.8M** annually. The biggest opportunity lies with platforms that have large volume but lower success rates - particularly FTX, OKX, and Huobi.

While the potential gains are substantial, we don't yet understand why success rates differ so much between platforms. Some platforms consistently perform better than others, suggesting there are specific operational or technical factors at play. This analysis identifies which platforms should be prioritized for deeper investigation to unlock these improvements.

## Assumptions & Methodology
### Assumptions
- The data represents Company X's crypto operations across various liquidity provider platforms
- Improving success rates would directly translate to increased transaction volume 
- Average fee rate of 2.5% across all platforms for revenue calculations

### Data Cleaning & Preparation
- Loaded raw transaction data into Jupyter notebook for initial exploration
- Checked for missing values, outliers, zeros, negative amounts, and duplicate records
- Found and removed duplicate transactions
- Aggregated transaction-level data to monthly view (limited dataset made weekly aggregation less meaningful)

### Methodology
I focused on the revenue impact chain:
**Revenue ← Volume ← User Count ← Transaction Success Rate**

## How to Use the Analysis Sheet
The analysis is in the [Analytics gs](https://docs.google.com/spreadsheets/d/1YZcSEXWBIVPqWnFkvasLL4SsM8o5qXO84TS5FQTLK3A/edit?usp=sharing) file, *Analytics* sheet. Other sheets contain aggregated data from jupyter notebook.
### Sheet Structure
1. KPI Dashboard - Shows the main business metrics: Revenue → Volume → User Count, plus market share (Volume based)
2. Transaction Success Rate Behavior - 
Monthly success rates broken down by each platform to see trends over time.
3. Prioritization for Further Analysis - 
Identifies which platforms offer the biggest volume/revenue opportunities for improvement efforts.
4. Appendix - Correlation Check -
Shows how platform success rates correlate with each other over the last 12 months.

The logic flows from high-level business impact down to specific platform performance, ending with which platforms to focus on first.
