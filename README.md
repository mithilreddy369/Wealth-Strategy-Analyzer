Wealth Strategy Analyzer 📈

A powerful, single-page financial dashboard that allows users to simulate, visualize, and compare different wealth generation strategies in real-time.

Unlike basic calculators that simply divide annual returns by 12, this tool uses industry-standard financial formulas (Effective Monthly Rate & Annual Compounding) to ensure results match top investment platforms like Groww and 5paisa.

🚀 Features

Multi-Strategy Comparison: Simultaneously calculate returns for:

Regular SIP: Fixed monthly investments.

Fixed Top-Up: Increasing SIP by a fixed amount (e.g., +₹500 every 6 months).

% Step-Up: Increasing SIP by a percentage (e.g., +10% yearly).

Lumpsum: One-time investment with annual compounding.

Real-Time Analysis: Instant updates as you adjust sliders or inputs.

Strategy DNA: A visual bar chart comparing the "wealth potential" of different strategies side-by-side.

Yearly Projections: A responsive data table showing the detailed breakdown of investment vs. value over time.

Goal Tracking: Automatically calculates the year in which a specific financial target (e.g., ₹10 Cr) is achieved.

Modern UI/UX:

Fully Responsive (Mobile, Tablet, Desktop).

Dark / Light Theme toggle with persistence.

Clean, dashboard-style layout.

🧮 Calculation Logic

This analyzer differentiates itself by using precision financial logic:

Effective Monthly Rate: Instead of Annual Rate / 12, we use the Geometric Mean: (1 + r)^1/12 - 1. This ensures that a 24% annual return is exactly 24% at the end of the year, preventing the "inflated return" error found in simpler calculators.

Lumpsum Compounding: Uses standard Annual Compounding formula $A = P(1+r)^t$ rather than monthly compounding, aligning with mutual fund standards.

SIP Formula: Uses the "Annuity Due" method (investment at the start of the month), which is the standard for Mutual Fund SIPs.

🛠️ Tech Stack

HTML5 - Semantic structure.

CSS3 - Custom properties (variables) for theming, Flexbox/Grid for layout. No external CSS frameworks used.

JavaScript (ES6+) - Core logic, DOM manipulation, and financial algorithms. No external libraries used.

