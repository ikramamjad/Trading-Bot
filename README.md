# Trading-Bot
Here’s the strategy. It will:
Enter a long trade when the 50-period MA crosses above the 200-period MA.
Enter a short trade when the 50-period MA crosses below the 200-period MA.
Plot both MAs on the chart for visibility.
Let me walk you through the step-by-step process to install and run this Pine Script strategy in TradingView:
📌 Step 1: Open TradingView
Go to TradingView
Log in (or create a free account if you don’t already have one).
📌 Step 2: Open Pine Script Editor
Open any chart (e.g., BTCUSDT, ETHUSDT, XAUUSD, etc.).
At the bottom of the screen, find and click “Pine Editor”.
📌 Step 3: Copy the Strategy Code
Delete any default code in the Pine Editor.
Copy the strategy code I gave you and paste it into the editor.
📌 Step 4: Add the Script to the Chart
Click the “Add to Chart” button above the editor.
If there are no errors, your MAs (blue & red) will appear on the chart.
You’ll also see trades (longs/shorts) automatically plotted.
📌 Step 5: Open Strategy Tester
At the bottom, click “Strategy Tester”.
You’ll now see backtest results:
Profit/Loss
Number of trades
Win rate, drawdown, etc.
📌 Step 6: Customize Parameters
On the chart, go to Settings (⚙️) → Inputs.
You can change Fast MA (default 50) and Slow MA (default 200).
Works on any symbol and timeframe (crypto, gold, stocks, forex).
✅ That’s it! You now have a fully running backtestable strategy in TradingView.
If you want to run it for live trading (broker integration), you’ll need to connect your TradingView account to a supported broker or crypto exchange.
