# Monte Carlo Retirement Simulator

A fast, responsive, single-page web application that models retirement portfolio longevity utilizing Monte Carlo simulations. Built with pure HTML5, Tailwind CSS, and vanilla JavaScript (powered by Chart.js).

## Features

- **Monte Carlo Simulations**: Instantly run thousands of randomized market return paths to stress-test your portfolio against sequence-of-returns and inflation risks.
- **Smart Withdrawal Strategies**:
  - **Standard 4% Rule**: Fixed initial withdrawal adjusted annually for inflation.
  - **Guyton-Klinger (Simplified)**: Pauses inflation adjustments after negative portfolio-return years to preserve capital.
  - **Floor & Ceiling**: Dynamic withdrawals bounded by percentage drops and peaks.
  - **Age-Based**: RMD-style withdrawals based on a 90-year life expectancy.
  - **3-Bucket Strategy**: Simulated cash buffer approach to weather equity downturns.
- **Reverse Scenario Planners**:
  - **Target Corpus**: Automatically calculates the exact nest egg required to achieve a 95% success rate for your timeline.
  - **Max Payout**: Determines the maximum safe initial withdrawal for your current corpus.
- **Fully Customizable Parameters**: Define your own Asset Allocation percentages (Equity, Debt, Cash), mean return vs. standard deviation expectations, and custom inflation bounds.
- **Premium UI & Data Visualization**: Fully responsive, mobile-optimized dark mode interface presenting real-time Spaghetti graphs and Depletion Histograms. Localized to Indian Rupees (₹) with smart comma formatting.

## Usage

Because the application runs entirely client-side, there are no complicated installation steps, backend servers, or build processes required.

1. Just download and open `index.html` directly in any modern web browser.
2. Adjust your baseline metrics and hit **Run Simulation**!
