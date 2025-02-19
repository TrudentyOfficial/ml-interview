# ml-interview
Take-Home Problem-Solving: Customer Trust Score &amp; Identity Mapping


**Instructions**:

You are given structured data for browser fingerprinting and open banking - account & transaction details, which can be used to give a Customer Trust Score (Friendly-fraud detection) and map identities across networks (in folder **Identity Mapping** & **Open Banking**).

Use this data format to answer the following questions and propose solutions for fraud detection, synthetic identity detection, and network-wide identity mapping.

Explain your reasoning, algorithms, and approach where applicable.

**Section 1: Customer Trust Score / Fraud Detection (Friendly Fraud)**

**Section 2: Identity Mapping (Synthetic Identities, & Syndicate Activity)**

Please find the detailed questions and guidelines in **Take-home Problem Solving.ipynb** file 


# Deliverables
- **Technical Report.pdf** -  A comprehensive guideline and analysis report detailing the approach, architecture decisions, feature engineering, development process, and model insights.
- **Implementation.ipynb** - Implementation for some part of feature engineering mentioned in the Technical Report for identifying high-risk customers and calculate Customer Trust Score.
- **Deployment Strategy.pdf** A detailed deployment strategy with:
  + Infrastructure setup (Cloud, On-Prem, Hybrid)
  + Model Deployment (API, Batch Processing, Edge)
  + CI/CD Pipelines for ML
  + Real-time Streaming Auto-retraining & Monitoring.

**NOTE**: After some analysis of the provided data, we can see that this data might be synthetically duplicated with the same values or the provided data is not sufficient to train statistical ML models. So we will suggest some insights and highlight techniques based on the common knowledge of statistical Machine Learning models as well as other rule-based models for fraud detection.

