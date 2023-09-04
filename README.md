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

1. Fork and clone the project repo: https://github.com/z-q-ying/forage-jpmc-swe-task-3.git
2. Create a new virtual environment in the project root. Pycharm can do this automatically for you using the **configure python interpreter** option in settings.
3. If you already have access to npm on your system, you can skip this step. Otherwise, you will need to acquire it by following the instructions [here](https://nodejs.dev/en/learn/how-to-install-nodejs/) (npm comes bundled with nodejs):  For this project to work, you must have **node 18.10.0** installed on your machine. Ensure you have the correct version by running **node -v** in your terminal. If you do not, consider using nvm to install the correct version for you.
4. Install the necessary dependencies by running **npm install** from the project repo
5. Start the python server by running server3.py from the project repo like so: **python datafeed/server3.py** (note it’s important you run it from the root of the project repo)
6. Once you start the web server on your local machine, click **Start Streaming Data** just once to load the data feed

### What to Expect
Upon activation, the data feed will display the ratio of Stock A's price to Stock B's price, refreshing continuously at intervals of 0.1 seconds. This ratio is the key metric we're tracking — not the individual stock prices. The reason for this is to help traders identify opportunities based on changes in the historical correlation between the two stocks.

![forage_jPMC_start_streaming](https://github.com/z-q-ying/forage-jpmc-software-engineering/assets/116849653/7898d9af-5304-41aa-809b-8709a578100f)

### Advanced Features
The graph also includes upper and lower bounds based on a historical correlation to help traders identify trading opportunities more easily. When the ratio crosses these bounds, an alert is triggered. In this demo, the red alert line appears whenever the ratio deviates by +/- 3% from the 12-month historical average. In a real-world scenario, traders might set this to +/- 10% based on a 12/24-month historical average, depending on their specific trading strategy.

![forage_jPMC_trigger_alerts_1](https://github.com/z-q-ying/forage-jpmc-software-engineering/assets/116849653/579c0ebe-f41c-4f1f-8f24-2d170adc6e0f)

### Why This Matters
Traders aim to monitor the weakening or strengthening of correlation between two historically related stocks. A change could signify a trade opportunity, such as buying the underperforming stock and selling the outperforming one, with the expectation that their prices will eventually converge.

![forage_jPMC_trigger_alerts_2](https://github.com/z-q-ying/forage-jpmc-software-engineering/assets/116849653/337223f0-34f2-4194-b785-afa339e9fed2)

## Acknowledgments
This project is part of the JP Morgan Chase's Software Engineering virtual experience program.

## Certificate
Feel free to checkout my [Completion Certificate](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/J.P.%20Morgan/R5iK7HMxJGBgaSbvk_J.P.%20Morgan_XH88dvsP4RZbP5AAk_1693784026197_completion_certificate.pdf)!
