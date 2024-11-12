# 474 Project Overview


:::mermaid
graph LR  
  A[Vancouver Theft Analysis]  
  A --> B[Data Preprocessing]  
  A --> C[Spatiotemporal Analysis]  
  A --> D[Pattern Recognition]  
  A --> E[Predictive Modeling]  

  B --> B1[Data Cleaning & Validation]  
  B --> B2[Feature Engineering]  
  B --> B3[Data Integration with Neighborhood Info]  

  C --> C1[Theft Distribution by Neighborhood]  
  C --> C2[Peak Time Analysis]  
  C --> C3[Seasonal Trends]  

  D --> D1[High-crime Areas Identification]  
  D --> D2[Theft Type Patterns]  
  D --> D3[Environmental Factors Analysis]  

  E --> E1[Location-based Risk Assessment]  
  E --> E2[Time Series Prediction]  
  E --> E3[ML Model Development]  

  classDef default fill:#f9f,stroke:#333,stroke-width:2px;  
  classDef section fill:#bbf,stroke:#333,stroke-width:2px;  
  class A,B,C,D,E section;
:::