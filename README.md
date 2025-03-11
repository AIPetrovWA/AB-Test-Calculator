<<<<<<< HEAD
# AB-Test-Calculator
AB Test Calc
=======
# A/B Test Sample Size and Significance Calculator

## Overview
This is a **GUI-based A/B Test Calculator** that helps users determine:
- The required **sample size** for an A/B test.
- The **test statistic** for binary (conversion rate) and averages (mean-based) data.
- Whether the result is **statistically significant** and/or **practically significant**.
- A **visual representation** of the hypothesis test using a normal distribution plot.

The application is built using **Python** with **PyQt5** for the GUI and **Matplotlib** for visualization.

## Features
- **Supports Two Types of Data**
  - **Binary Data** (e.g., conversion rates)
  - **Averages Data** (e.g., average revenue per user)
- **Sample Size Calculation**
  - Uses statistical formulas to determine the minimum sample size required.
- **Hypothesis Testing**
  - Calculates the test statistic for Z-test (binary) or T-test (averages).
  - Allows selection of **one-tailed (left/right) or two-tailed tests**.
- **Statistical & Practical Significance**
  - Determines if the result is statistically significant.
  - Checks for practical significance based on Minimum Detectable Effect (MDE).
- **Visual Representation**
  - Displays a normal distribution plot with rejection regions.
- **User-Friendly Interface**
  - Modern GUI with tooltips and step-by-step guidance.

## Installation
### **Dependencies**
Make sure you have **Python 3.7+** installed. Then, install the required dependencies using:

```bash
pip install PyQt5 matplotlib scipy numpy
>>>>>>> fdf52b8 (Initial commit: A/B Test Sample Size Calculator)
