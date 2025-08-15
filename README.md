Master Metadata Spreadsheet for Multimodal Freight Databases
Overview
This GitHub repository contains the master metadata spreadsheet for freight-related datasets, as described in the manuscript "On Multimodal Freight Databases for Scalable Global-Local Transport Research and Applications" (Submission ID: 6f7971da-99e6-4b3b-9848-58a6b5f7c460, under review at Transportation, Springer Nature). The spreadsheet catalogs over 50 datasets from the United States, European Union, and China, organized into nine core categories (socioeconomic-demographic, commodity/goods, multimodal networks, ports, trade, flow databases, geographical references, regulation/code, and transportation means). It supports reproducible research in global-local freight transportation modeling.
Version: 1.0
Date: August 15, 2025
Authors: Muhammad Haroon, Guoqiang Shen (corresponding), Jinhua Zhao, Pengyu Zhu
details. Reuse is permitted with proper attribution.
Repository URL:  https://github.com/haroonbaloch770/Master-Metadata-Spreadsheet-for-Multimodal-Freight-Databases-in-the-US-EU-and-China
Files Included
•	Unified Metadata field.xlsx: The primary Excel file with all metadata in a single sheet (for easy querying). Columns are based on the unified metadata fields from Table 1 in the manuscript.
•	The Master Metadata Spreadsheet (dataset).xlsx: A xlsx export for broader compatibility (e.g., import into Python, R, or GIS tools).
Spreadsheet Structure
The spreadsheet has one row per dataset and the following columns:
•	Region: Data coverage (e.g., U.S., EU, China).
•	Dataset Name: Official name of the dataset (e.g., American Community Survey).
•	Agency/Source: Organization responsible (e.g., U.S. Census Bureau).
•	Spatial Coverage: Geographic granularity (e.g., State, County, MSA).
•	Temporal Coverage: Time period and frequency (e.g., Annual, Every 5 years).
•	Key Variables: Main fields/metrics (e.g., Population, Employment by NAICS).
•	Access Method: How to obtain the data (e.g., API URL, web portal).
•	Data Format: Available formats (e.g., CSV, Shapefile).
•	Cost/License: Fees or licensing (e.g., Free, Subscription).
Additional columns (if included): Quality ratings for completeness, timeliness, accuracy (from Section 2.5 of the manuscript).
Data is compiled from Appendix A Tables A.1–A.9 in the manuscript, flattened into a unified view.
Usage Instructions
1.	Download and Query: Clone the repo or download the files. Use Excel/Google Sheets filters to search by region, category, or coverage. For advanced analysis, import into tools like Pandas (Python) or dplyr (R) for sorting, filtering, or joining with other data.
2.	Integration: Cross-reference with the manuscript's harmonization workflows (Section 6) for spatial/temporal/commodity alignment.
3.	Updates: This is version 1.0 (as of August 15, 2025). Future versions will be committed to this repository. Check original sources for the latest updates, as frequencies vary (e.g., annual vs. quinquennial). Feel free to fork and submit pull requests for contributions.
4.	Limitations: Metadata is based on sources available at compilation time; verify access links, as they may change. No proprietary data is included—all sources are public.
Citation
Please cite both the manuscript and this repository:
•	Manuscript: Haroon, M., Shen, G., Zhao, J., & Zhu, P. (2025). On Multimodal Freight Databases for Scalable Global-Local Transport Research and Applications. Transportation. [DOI or link once published].
•	Dataset: Haroon, M., Shen, G., Zhao, J., & Zhu, P. (2025). Master Metadata Spreadsheet for Multimodal Freight Databases in the US, EU, and China [Data set]. GitHub. https://github.com/haroonbaloch770/Master-Metadata-Spreadsheet-for-Multimodal-Freight-Databases-in-the-US-EU-and-China 
Contact
For questions, updates, or contributions:
Muhammad Haroon (muhammadharoon@zju.edu.cn)
Guoqiang Shen (corresponding author: gshen214@zju.edu.cn)
This repository promotes open science in freight transportation research.
