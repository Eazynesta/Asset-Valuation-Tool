#Sovren Valuation Tool

This TradingView indicator compares the relative strength of a chosen symbol against up to three reference symbols. It normalizes these values over a customizable lookback period, presenting them on a 0-100 scale to help identify overbought or oversold conditions and market trends.

    Features
Compare Multiple Symbols: Compare the relative strength of your symbol against up to three reference symbols.
Normalized Output: Relative strength is normalized on a scale of 0-100, allowing for clear comparison.
Customizable Lookback Period: Set the lookback period to determine the range for normalization (default is 75 bars).
Visualization: The indicator plots the relative strength values of each reference symbol on the chart for easy interpretation.

    How It Works
The tool fetches the closing prices for your chosen asset and compares them with the prices of up to three reference symbols.
It calculates the relative strength for each reference symbol by dividing the current price by the reference price.
The historical maximum and minimum relative strengths over the chosen lookback period are used to normalize these values on a 0-100 scale.
The normalized values are plotted on the chart, with lines at 20 and 80 to help highlight potential overbought or oversold conditions.

    How to Use
Select Symbols: Choose the symbol you want to analyze and up to three reference symbols (e.g., GC1! for Gold, DXY for the Dollar Index, and EURUSD).
Customize Options: Toggle which reference symbols to display and adjust the number of decimal points or the rescale length.
Interpret the Chart: Use the normalized values to determine relative strength and watch for extremes (near 20 or 80) that may signal potential reversals.

    Input Options
Reference Symbol 1/2/3: Select the reference assets for comparison.
Show Reference Symbol 1/2/3: Toggle the visibility of each reference symbol's relative strength.
Decimals of Precision: Set the number of decimal places for displayed values.
Rescale Length: Define the lookback period for normalization (default: 75).

    Visual Output
Blue Line: Normalized Relative Strength for Reference Symbol 1
Purple Line: Normalized Relative Strength for Reference Symbol 2
Orange Line: Normalized Relative Strength for Reference Symbol 3
Horizontal Lines: Levels at 20 and 80 to indicate potential overbought or oversold conditions.

    Example Usage
Add the indicator to your TradingView chart.
Select your asset (e.g., AAPL) and reference symbols (e.g., DXY, GC1!, EURUSD).
Observe how the asset’s relative strength changes and compare against reference symbols.
