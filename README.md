# Saskatchewan Farm Credit Risk & Sensitivity Model

A dynamic, formula-driven credit underwriting and risk sensitivity model for agricultural loan assessment.

## Project Overview
This project models a term mortgage underwriting scenario for a **2,500-acre grain farm** in Saskatchewan seeking a **$3.0M loan**. 

The model evaluates operational cash flows based on crop yields, applies industry-standard operating ratios, and stress-tests the farm's repayment capacity against market fluctuations.

## Key Deliverables
* **Saskatchewan_Farm_Credit_Model.xlsx**: The complete Excel model featuring active financial formulas, amortization schedules, and conditional formatting risk matrices.

## Core Features & Methodology
* **Crop Production Assumptions**: Modeled revenue for Canola and Wheat based on acreage, crop price ($/bushel), and yield (bushels/acre).
* **Underwriting Metrics**: Calculated Net Operating Income (NOI), Cash Available for Debt Service (CADS), and the **Debt Service Coverage Ratio (DSCR)** using the Excel `PMT` formula for annual debt service.
* **5x5 Sensitivity Matrix**: Built a dynamic risk table stress-testing the DSCR across a range of Canola prices ($11.50 to $15.50) and crop yields (38 to 48 bu/ac).
* **Conditional Formatting**: Used a colour-coded heat map to instantly highlight where the farm's DSCR falls below the 1.25x underwriting benchmark.

## Tools & Concepts Used
* **Microsoft Excel**: Dynamic Formulas, PMT function, Data Tables, Conditional Formatting, Financial Underwriting
* **Credit Analysis**: Debt Service Coverage Ratio (DSCR), Cash Flow Projections, Sensitivity Stress-Testing
