# Supplementary Materials

## Overview

**Supplementary Materials** is a structured collection of the empirical data, modelling assumptions, cost parameters, and computational results supporting the study **“A Cost-Efficiency Frontier for Humanoid Robot Deployment in Parcel Sorting.”**

## Appendix Structure

| Appendix       | Main Content                                         | Primary Function                                                       |
| :------------- | :--------------------------------------------------- | :--------------------------------------------------------------------- |
| **Appendix A** | Salary and labour-cost data                          | Supports the estimation of human sorting costs                         |
| **Appendix B** | Worker efficiency and sorting-quality parameters     | Supports the estimation of human productivity and operational quality  |
| **Appendix C** | Humanoid robot prices, BOM data, and ownership costs | Supports the estimation of robot deployment and operating costs        |
| **Appendix D** | Baseline human labour-cost inputs                    | Supports the construction of the baseline human labour-cost parameters |
| **Appendix E** | Detailed computational results                       | Supports result verification and model reproduction                    |

## Appendix A: Salary Component Data Package

Appendix A contains the salary and employment data collected for sorting and warehouse positions at SF Express and JD Logistics.

The tables are organized into three functional groups:

* **Data definitions and calculation rules — Table A1**
  Explains the salary fields, salary-normalization procedures, annual cash-wage calculation, employer labour-cost estimation, benefit categories, and data-reliability considerations.

* **Brand-level and city-level summaries — Tables A2–A5**
  Compare salary levels and estimated employer labour costs across companies and cities. These tables also summarize the frequency of employment components such as night-shift arrangements, social insurance, housing funds, accommodation, meal allowances, overtime, performance pay, and bonuses.

* **Role-level source records — Tables A6–A10**
  Report the individual job observations underlying the aggregated results. The tables identify the company, city, employer, job title, employment type, salary range, benefits, shift arrangement, work content, original source, and verification status of each observation.

## Appendix B: Worker Efficiency and Sorting-Quality Parameters

Appendix B contains the productivity and sorting-quality parameters used to estimate human processing capacity and compare human and robotic sorting performance.

The tables are organized into five functional groups:

* **Base worker-efficiency inputs — Table B1**
  Summarizes the baseline values for hourly throughput, shift duration, effective working time, peak-period productivity loss, and effective parcels processed per shift.

* **Evidence classification and parameter construction — Tables B2–B4**
  Classify each parameter according to its empirical basis, report its numerical value, and explain how it is incorporated into the model. These tables distinguish public observations, system-level benchmarks, worker-level evidence, and modelling assumptions.

* **Parcel-type processing characteristics — Tables B5–B6**
  Describe differences in manual processing efficiency and robotic suitability across parcel categories. The tables specify the expected human productivity, robot-compatible parcel share, and relevant operational limitations for each parcel type.

* **Scenario-level productivity and quality inputs — Tables B7–B8**
  Provide the productivity, peak-loss, wrong-sorting, missed-scan, damage, and rework parameters used in the computational scenarios.

* **Sources and limitations — Tables B9–B10**
  Document the supporting sources, source URLs, intended uses, reliability levels, and limitations of the worker-efficiency evidence.

## Appendix C: Humanoid Robot Price, BOM and Total Ownership Cost Data

Appendix C contains the robot price database and the cost assumptions used to estimate the economic consequences of humanoid robot deployment.

The tables are organized into six functional groups:

* **Database overview and model comparison — Tables C1–C2**
  Summarize the structure of the robot-cost dataset and compare the included robot models, public prices, market positions, and estimated five-year total ownership costs.

* **Robot price records — Tables C3–C5**
  Report robot model identities, price status, original price ranges, converted prices, functional capabilities, source URLs, and source-quality notes.

* **Bill-of-materials benchmarks — Tables C6–C7**
  Provide component-level cost benchmarks for major humanoid robot systems and document the assumptions and sources supporting these estimates.

* **Total ownership cost construction — Tables C8–C10**
  Estimate upfront deployment costs, annual operating costs, depreciation, residual value, and five-year total ownership cost. The cost categories include parcel-handling adaptation, scanning equipment, safety systems, integration, maintenance, software, electricity, operational personnel, and downtime.

* **Cost-category definitions and scenario construction — Tables C11–C12**
  Define each cost category, describe its default estimation method, identify the information required from vendors or pilot projects, and explain the construction of low, base, and high cost scenarios.

* **Numerical assumptions and supporting evidence — Tables C13–C14**
  Report the numerical values used in the economic model together with their calculation notes, source links, and adjustable ranges.

## Appendix D: Baseline Human Labour Cost Inputs

Appendix D contains the baseline human labour-cost inputs used in the economic evaluation. It consolidates the representative salary, employer contribution, allowance, overtime, benefit, and annual labour-cost parameters used to construct the baseline human sorting-cost estimates.

## Appendix E: Detailed Computational Results

Appendix E contains the complete numerical outputs generated by the economic evaluation, simulation, and optimization models.

The tables are organized into nine functional groups:

* **Main results dashboard — Tables E1–E2**
  Summarizes the principal break-even results and the seasonal throughput requirements calculated for the Unitree G1 benchmark.

* **Model parameters — Table E3**
  Lists the parameters used in the analysis, including their definitions, values, units, roles in the model, and calibration rationale.

* **Interactive calculations — Table E4**
  Demonstrates how robot price, robot throughput, logistics company, and operating season can be combined to evaluate user-defined deployment scenarios.

* **Unitree G1 thresholds — Table E5**
  Reports the robot-throughput levels required for the Unitree G1 to satisfy unit-cost parity and the specified investment-payback criterion.

* **Price-efficiency frontier — Tables E6–E7**
  Show the maximum economically acceptable robot price at different levels of robot sorting efficiency.

* **Simulation grid — Tables E8–E10**
  Report the complete results across combinations of robot prices, robot efficiencies, logistics companies, and seasonal operating conditions. The outputs include economic feasibility, optimal robot and worker quantities, automation share, total operating cost, and cost savings.

* **Hybrid workforce optimization — Tables E11–E12**
  Provide the optimal robot-human staffing configurations for the Unitree G1 under alternative robot-throughput assumptions.

* **Model formulas — Table E13**
  Presents the mathematical formulas used to calculate annualized robot costs, output capacity, break-even throughput, maximum acceptable robot price, payback thresholds, and optimal hybrid staffing decisions.

* **Data sources — Table E14**
  Consolidates the sources used in the computational analysis and identifies the principal limitations associated with each input category.
