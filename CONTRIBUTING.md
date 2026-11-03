# Contributing

This repository is used for the weekly AAPL (Apple Inc.) options expiration review.

## Adding this week's data

1. Pull the latest live option chains for AAPL from Yahoo Finance.
2. Identify the three soonest upcoming expirations.
3. Open one tracking issue per expiration, titled `Expiry YYYY-MM-DD`, containing:
   - this expiration's at-the-money strike,
   - the highest-open-interest call strike,
   - the highest-open-interest put strike,
   - the share price used.
4. Update `expirations.md` on the tracking branch and open a pull request into the default branch.

## Notes

- Keep all market figures sourced from live data on the day of the run.
- Where a number looks odd, report exactly what the source returned rather than
 subseting silently.
