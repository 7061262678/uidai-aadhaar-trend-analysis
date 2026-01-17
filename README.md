\# Unlocking Societal Trends in Aadhaar Enrolment and Updates



\## Overview

This project analyses Aadhaar enrolment, demographic update, and biometric update datasets released by UIDAI to identify meaningful societal trends, regional patterns, and anomalies that can support informed decision-making and system improvements.



\## Datasets Used

\- Aadhaar Enrolment Dataset

\- Aadhaar Demographic Update Dataset

\- Aadhaar Biometric Update Dataset



(All datasets are provided by UIDAI and analysed in aggregated form.)



\## Methodology

\- Data inspection and merging of large chunked files

\- Data cleaning and standardisation

\- Univariate analysis (state-wise enrolment trends)

\- Bivariate analysis (state vs update type)

\- Anomaly detection using statistical thresholds

\- Visualisation of key findings



\## Project Structure

uidai\_project/

├── scripts/

├── data/

├── outputs/

│ └── plots/





\## Key Insights

\- Significant regional variation in Aadhaar enrolment

\- High dependency on demographic updates in certain states

\- Limited number of states showing anomalously high biometric update volumes



\## How to Run

All analysis scripts can be executed using Command Prompt:

python scripts/data\_cleaning.py

python scripts/univariate\_analysis.py

python scripts/bivariate\_analysis.py

python scripts/anomaly\_detection.py

python scripts/visualisation.py





\## Impact

The findings can help UIDAI identify service demand patterns, regional stress points, and opportunities for improving enrolment and update infrastructure.





