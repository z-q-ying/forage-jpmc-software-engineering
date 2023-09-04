# 🏦 JP Morgan Chase Software Engineering Virtual Experience Program

## 📋 Overview

This repository contains my work for JP Morgan Chase's Software Engineering Virtual Experience Program. The primary focus of the project is to build and enhance a financial data feed for a trader's dashboard to help identify stocks that are under or over-valued.

### 💻 Technologies Used
- JavaScript
- TypeScript
- Perspective (by JPMorgan Chase)
- HTML & CSS
- Python
- React

---

## 🚀 Getting Started

### 📜 Prerequisites

- Node.js version `18.10.0`
- Python 3.x

### 🛠 Installation Steps

1. **Clone the Repository**:  

   ```bash
   git clone https://github.com/z-q-ying/forage-jpmc-swe-task-3.git

2. **Virtual Environment:**
Navigate to the project root and create a Python virtual environment. You can do this automatically in PyCharm via the Configure Python Interpreter option.

3. **Node.js and npm:**
If you don't have npm, [install it following these instructions](https://nodejs.dev/en/learn/how-to-install-nodejs/). Make sure you have Node version 18.10.0
    ```bash
    node -v

4. **Start the Server:**
    ```bash
    python datafeed/server3.py

5. **Activate Data Feed:**
Once the web server is up, click **Start Streaming Data** to load the data feed.

---
## ⭐ Features

### 📈 Real-Time Data Feed
Upon activation, the dashboard will display the ratio of Stock A's price to Stock B's price, updating every 0.1 seconds. This ratio is our key focus, rather than the individual stock prices.

![forage_jPMC_start_streaming](https://github.com/z-q-ying/forage-jpmc-software-engineering/assets/116849653/7898d9af-5304-41aa-809b-8709a578100f)

### 🚨 Alert System
The dashboard also features alert lines based on historical data. When the stock ratio crosses these lines, an alert is triggered.

![forage_jPMC_trigger_alerts_1](https://github.com/z-q-ying/forage-jpmc-software-engineering/assets/116849653/579c0ebe-f41c-4f1f-8f24-2d170adc6e0f)

### 🤔 Why This Matters
The project aims to help traders monitor the weakening or strengthening of the correlation between two historically related stocks. A change could signify a trade opportunity.

![forage_jPMC_trigger_alerts_2](https://github.com/z-q-ying/forage-jpmc-software-engineering/assets/116849653/337223f0-34f2-4194-b785-afa339e9fed2)

### Advanced Features
The graph also includes upper and lower bounds based on a historical correlation to help traders identify trading opportunities more easily. When the ratio crosses these bounds, an alert is triggered. In this demo, the red alert line appears whenever the ratio deviates by +/- 3% from the 12-month historical average. In a real-world scenario, traders might set this to +/- 10% based on a 12/24-month historical average, depending on their specific trading strategy.

### Why This Matters
Traders aim to monitor the weakening or strengthening of correlation between two historically related stocks. A change could signify a trade opportunity, such as buying the underperforming stock and selling the outperforming one, with the expectation that their prices will eventually converge.

---

## 👏 Acknowledgments
This project is part of the JP Morgan Chase's Software Engineering virtual experience program.

## 🏆 Certificate
Feel free to checkout my [Completion Certificate](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/J.P.%20Morgan/R5iK7HMxJGBgaSbvk_J.P.%20Morgan_XH88dvsP4RZbP5AAk_1693784026197_completion_certificate.pdf)!
