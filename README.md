# pine
Instruction Template

Create Pine Script code to capture high-probability long entries using support, breakout, and retest logic:

1. Detect Support Levels

Identify pivot lows (recent 3–10 bars) as potential support.

Include SMA150 or other moving averages as dynamic support.

Include zones where price has repeatedly bounced (≥2 times).

2. Detect Breakouts

Identify breakout above recent resistance (pivot highs) or above SMA150.

Confirm breakout with volume spike and/or momentum indicators (MACD, RSI, ATR).

3. Detect Retests

Track price returning to a breakout or support level.

Consider multiple retests (≥1) after breakout.

Only mark retest as valid if price closes above support for long entry.

4. Entry Conditions

Long entry triggers when:

Price breaks above confirmed resistance OR SMA150, and

Retests support and holds, and

Volume or momentum confirms strength.

5. Stop-Loss / Risk

Place stop-loss slightly below last support or swing low.

Risk per trade ≤1–2% of account balance.

6. Optional Filters

Timeframe multi-confirmation: 4H, 1D, 1W.

Only take trades aligned with bullish trend across at least 2 higher timeframes.
