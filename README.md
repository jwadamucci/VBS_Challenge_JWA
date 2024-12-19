# VBS_Challenge_JWA
this contains the VBS Challenge files for Bootcamp

# Screenshots
There are 4 screenshots, showing the topmost rows of each Quarter's tab, which include:  
  *The raw daily data for alphabitized ticker symbols in Columms A-G
  * The Summary Table,in Columns I through L, aggregating information for each unique Ticker symbol, which shows:
      1) change in price over the quarter, in dollars (colored-coded red for decrease, green for increase)
      2) the Percent change over the quarter
      3) the total volume of shares traded over the quarter
  * A small table (referred to as "the Podium" in the code file) whcih contains
      1) The symbol with the greatest percent increase, i.e Greatest % Increase
      2) the symbol with the greatest percent decrease, i.e. Greatest % Decrease
      3) the symbol with the most shares traded over the period, i.e. Greatest Total Volume
# Notes
The coding results in real-time updating which is interesting to watch, since each iteration of the raw data updates the summary table appropriately.  
However, this causes a big hit to performance, and in a production environment would need to be assessed for optimization.
