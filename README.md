PYMACEUTICALS CHALLENGE
1.	Project Overview and Purpose:
Utilizing the complete data from Pymaceuticals, Inc.'s most recent animal study, a comparison of their novel therapy, Capomulin, against other treatment regimens is required. This includes generating all necessary tables, figures, and listings (TFLs) for the technical report of the clinical study, along with a top-level summary of the study results.
2.	Dataset Description:
Two CSV datasets are being used to generate the TFLs and summary, both located in the data folder:
•	Mouse_metadata.csv: Contains subject-level information, including Mouse ID, Drug Regimen, Age, and Weight.
•	Study_results.csv: Provides additional subject-level data, including testing timepoints and tumor-related information such as volume and metastasis.
3.	Data Cleaning and Preprocessing:
Any potential duplicate information in the data was identified and addressed. Specifically, duplicate data for Mouse g989 was removed before proceeding with the analyses.
4.	Data Visualization Techniques and results
- Summary statistics by Drug Regimen-
 
- Bar charts - Total Observed Mouse Timepoints per Drug Regimen
 
- Pie charts - The distribution of female versus male mice
 
- Box and Whisker plots - The distribution of the tumor volume for each treatment group
 
- Line plot - Tumor volume vs. time point for a single mouse treated with Capomulin
 
- Scatter plots:
Mouse weight vs. the average observed tumor volume for the entire Capomulin regimen
 
The correlation between mouse weight and the average tumor volume is: 0.84.
 
5.	 Analysis
Overall, the summary of some high-level points about the results of the drug Capomulin compared to Ramicane and other drug products. Here’s a breakdown of the key points:
Capomulin and Ramicane have more observed timepoints than other treatments. It's suggested that further exploration is needed to determine if this is due to better tolerance by the mice, potentially leading to more time on the regimen. Investigating early mortality data during treatment might provide valuable insights for future drug development. Tumor Volumes:
Capomulin and Ramicane result in lower final tumor volumes compared to at least two other regimens. This may indicate a partial response to the drug. Additional data could help finalize critical drug decisions, such as determining the optimal duration of treatment, dose, formulation, etc. Correlation Between Mouse Weight and Tumor Volume:
A strong correlation is observed between mouse weight and the average tumor volume in the Capomulin group. Further exploration of other factors, such as gender or genetic variables, could provide more insights into the treatment effects of Capomulin.
6.	References 
Python code file pymaceuticals_final.ipynb is in pymaceuticals folder
Datasets are filed in the data folder
Expert learning assistant tool
