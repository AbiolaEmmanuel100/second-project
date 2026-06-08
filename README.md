# Data Quality Assessment & Assumptions

## Data Quality Review

Before conducting the analysis, the dataset was reviewed to validate the consistency and reliability of its variables.

Several fields appeared to be synthetically generated and did not always follow expected business relationships commonly found in real-world supply chain operations.

### Observations

* **Revenue Generated** did not consistently equal **Price × Number of Products Sold**.
* **Shipping Times** did not show a clear relationship with **Transportation Modes**.
* The **Costs** column lacked sufficient documentation to clearly identify its business meaning.
* Some operational metrics appeared to be independently generated rather than derived from related business processes.

## Analytical Assumptions

To ensure meaningful analysis, the following assumptions were adopted:

* **Manufacturing Costs** were treated as production expenses.
* **Costs** was interpreted as transportation or logistics cost.
* **Revenue Generated** was analyzed as provided in the dataset rather than recalculated.
* Supplier, product, transportation, and quality metrics were considered suitable for trend and performance analysis.
* Results should be interpreted as an analytical case study based on a synthetic dataset rather than actual company operations.

## Analytical Approach

Given the identified limitations, the analysis focused on:

* Product performance and revenue trends.
* Supplier performance evaluation.
* Manufacturing cost analysis.
* Logistics and transportation performance.
* Quality control and defect rate assessment.

This approach reflects a real-world data analytics workflow where data quality is assessed before insights are generated and business recommendations are made.
