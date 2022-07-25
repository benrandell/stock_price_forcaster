# stock_price_forcaster
## Methodology of Program
The program uses the relationships between a stock’s future prices and the stock’s historical data, with its respecting market index historical data, to create multiple multi-linear regression lines which are used to predict the stock’s next week’s future high and low price’s structure. The regression line is built using the stock’s historical “High(s), “Low(s)”, “Close(s)”, “Volume(s)” and the respective market index change in price, all over the past 9-time weeks to predict the future stock’s highest (roof) and lowest (floor) price. The program simultaneously runs new regression models over the past 10 sets of data to collect the accuracy of the regression models on the current 10-week period. This is through the deviation of the predictions compared to the actual highest and lowest price of the weeks. The final product shows the roof and floor prices for the next week, including the safety margins around the predictions shown by the accuracy deviation taken from the past 10 weeks. Finally, the trader can use this analysis to guide their trades through these “BUY” and “SELL” zones optimizing profit and minimize the risk in trading.

## Main Objective
This program is to be used as a tool for anyone that is participating in financial market trading, the objective is for the program is to work as a navigation system when the trader places their trades through out the week. This program simply highlights the highest and lowest prices throughout the week which act as "BUY" and "SELL" zones. Taking advantage of this tool the traders will assess the risk of the predictions by the deviation of the high and low prediction and make well guided trades to minimize risk and maximize profit.

## Results
After adjusting outliers, which were created by trend changes in the middle of the previous 10 weeks, the overall accuracy became very successful over stocks of a variety of different volatilises. These Outliers were handled by grabbing the deviation of the margin of error instead of the full range for our safety margins.

## Sample Dataset
The current sample datasets being use represents the technology based META stock’s historical data with the Nasdaq Composite representing its market index.

## Installation and Execution
1. clone repository to your preferred IDE (tested with VS code)
2. if using new data, grab data set from yahoo finance (Requirements in Jupyter lab file)
3. Click run all on jupyter lab file (the program does the rest of the work)
- if any questions, read through the very detailed markdown documentation in the code file 

## About Me
I am a 3rd year Wilfred Laurier student, currently enrolled in Business and Computer Science double degree. This is my second financial market related project, my first consists of an algorithmic trading program which removes the trader from the equation using real time analytics to preform trades.

## My Computer Programing Experience Consists of the following: 
Python Version 3.7.4, Bootstrap 4.5.2, HTML, JavaScript, CSS, jQuery, Pandas Library, MySQL, Flask, Django, Git System, Python Testing, Java, Excel VBA, C Programming, Relational Database Architecture, API Search Engine Architecture, Python Graphing Libraries, Artificial Intelligence/Machine Learning
