# JP Morgan Chase Software Engineering Virtual Experience Program

## Overview
This repository contains the tasks and accomplishments from the JP Morgan Chase's Software Engineering virtual experience program. The focus is on building and enhancing a financial data feed for a trader's dashboard to help them identify under/over-valued stocks.

**Technologies:**
- JavaScript
- TypeScript
- Perspective (by JPMorgan Chase)
- HTML & CSS
- Python
- React

## Demonstration
### Getting Started
To begin, start the web server on your local machine. Once the server is running, click **Start Streaming Data** just once.

### What to Expect
Upon activation, the data feed will display the ratio of Stock A's price to Stock B's price, refreshing continuously at intervals of 0.1 seconds. This ratio is the key metric we're tracking — not the individual stock prices. The reason for this is to help traders identify opportunities based on changes in the historical correlation between the two stocks.

![forage_jPMC_start_streaming](https://github.com/z-q-ying/forage-jpmc-software-engineering/assets/116849653/7898d9af-5304-41aa-809b-8709a578100f)

### Why This Matters
Traders aim to monitor the weakening or strengthening of correlation between two historically related stocks. A change could signify a trade opportunity, such as buying the underperforming stock and selling the outperforming one, with the expectation that their prices will eventually converge.

### Advanced Features
The graph also includes upper and lower bounds based on a historical correlation to help traders identify trading opportunities more easily. When the ratio crosses these bounds, an alert is triggered. In this demo, the red alert line appears whenever the ratio deviates by +/- 3% from the 12-month historical average. In a real-world scenario, traders might set this to +/- 10% based on a 12/24-month historical average, depending on their specific trading strategy.

## Acknowledgments
This project is part of the JP Morgan Chase's Software Engineering virtual experience program.

## Certificate
Feel free to checkout my [Completion Certificate](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/J.P.%20Morgan/R5iK7HMxJGBgaSbvk_J.P.%20Morgan_XH88dvsP4RZbP5AAk_1693784026197_completion_certificate.pdf)!
