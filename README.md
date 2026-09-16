Trading System

A Python-based automated intraday trading bot that connects to Schwab API.
Based on initial hypothesis that markets will trade sideways during oil crisis. Chose 3x leveraged QQQ and SPY for amplified swings and liquidity.
Built with purpose to explore systematic trading and quantitative strategy development.

Strategy

The trading strategy incorporates:

50-period and 150-period moving averages (5min candles)
35-period rolling standard deviation (5min candles)
Moving-average slope and momentum signals
Volatility-adjusted entry bands
Dynamic stop-losses
Trailing stops
Take-profit levels
End-of-day profit exits
Trading cool downs following losses

The system includes:

Real-time price streaming through the Schwab API
Automated limit-order execution
Fill-or-kill orders
Position synchronization with the brokerage account
Persistent state saved between restarts
Trade and polling logs
Token/session management
Duplicate-position safeguards
Automatic trading halts after predefined loss conditions
