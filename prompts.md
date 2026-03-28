# Retirement Simulation Web App Prompts

Below is the consolidated list of prompts and requests provided to guide the development of this application:

## Project Planning & Foundation
1. **Initial Planning**: "Develop a comprehensive, single-file (or modular) Web Application using HTML5, Tailwind CSS, and Vanilla JavaScript (ES6+) that performs a Monte Carlo simulation for retirement withdrawal strategies. Implement withdrawal strategies, inflation, sequence of returns risk, and dual forward/reverse simulation modes with interactive visualizations."
2. **Implementation Requirements**: "Build a fully functional, single-file Monte Carlo retirement simulator web application with configurable withdrawal strategies (4% rule, Guyton-Klinger), Chart.js visualizations, reverse calculation modes for target corpus/payout, and a premium responsive dark-mode UI with Indian-specific currency formatting."
3. **Mobile Audit & Responsiveness**: "Revise the existing Monte Carlo retirement simulator web application to ensure it is fully responsive and optimized for both mobile and desktop screen sizes. Refine the layout, CSS, and UI components for a seamless experience."

## Dashboard Iterations
4. **Chart Visualizations**: "Replace the spaghetti charts with fan chart."
5. **UI Scaling and Constraints**: "Limit the number of simulations to 1 million max. Show some spinwheen animation while the calculations are happening. Add spaghetti chart as well in addition to the fan chart and histogram."
6. **Responsive Adjustments**: "Fit the 3 charts in the same row while in the laptop screensize. It is ok to make their width smaller."
7. **Immediate Input Feedback**: "When we step out of the simulation field, immediately update the text on the run simulation button with the number."
8. **Documentation**: "Consolidate all the prompts so far in a single prompts.md file."
