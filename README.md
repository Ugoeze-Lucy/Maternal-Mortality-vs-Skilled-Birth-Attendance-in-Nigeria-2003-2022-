# Maternal-Mortality-vs-Skilled-Birth-Attendance-in-Nigeria-2003-2022

PROJECT OVERVIEW

This project explores the relationship between maternal mortality rates and births attended by skilled health personnel in Nigeria between 2003 and 2022.
The goal was to understand if increased access to skilled birth attendants correlates with reduced maternal deaths which is an important indicator of maternal health progress.

OBJECTIVES

-Analyze trends in maternal mortality and skilled birth attendance over time.

-Examine the strength and direction of the correlation between both indicators.

-Visualize the relationship to support public health policy discussions.

DATA SOURCE

Data was obtained from the World Health Organization (WHO):

Maternal Mortality Rate (per 100,000 live births) https://data.who.int/indicators/i/C071DCB/AC597B1

Births Attended by Skilled Health Personnel (%) https://data.who.int/indicators/i/F835E3B/1772666

TOOLS USED

-Python (Pandas, Matplotlib)

-Jupyter Notebook

-Microsoft Excel: for quick checks

DATA CLEANING AND PREPARATION

-Filtered datasets to include only Nigeria.

-Dropped irrelevant columns.

-Converted DIM_TIME to integer type for merging.

-Merged both datasets using a common time variable (Year).

-Sorted by year for trend analysis.

FINDINGS

-Maternal Mortality: Declined slightly from ~1090 (2003) to ~1016 (2022) per 100,000 live births.

-Skilled Birth Attendance: Increased from 35% (2003) to 51% (2022).

-Correlation: -0.53 (moderate negative relationship), as skilled birth attendance rises, maternal mortality tends to decrease.

INTERPRETATION

While the correlation indicates improvement, the reduction in mortality remains modest. This suggests that access alone may not be enough: quality of care, infrastructure, and health system funding remain key barriers.

VISUALIZATION

<img width="715" height="386" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/c3ef739f-80bb-4c8c-85ac-9a9d95122823" />
<img width="711" height="386" alt="Screenshot (48)" src="https://github.com/user-attachments/assets/b1c1816e-e0ab-49d1-8d2e-4a8ccf3dffab" />
<img width="755" height="373" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/8d006e04-45ea-4d45-a084-40fc63048856" />
<img width="413" height="94" alt="Screenshot (46)" src="https://github.com/user-attachments/assets/b845ca91-6ffc-459e-bd43-671834acd38b" />


KEY TAKEAWAYS

-Strengthening access to skilled birth attendants can significantly improve maternal outcomes.

-Nigeria’s progress is steady but still far from global targets (SDG 3.1: <70 deaths per 100,000).

-Continuous data-driven monitoring is crucial for achieving sustainable improvements in maternal health.

NOTE

Click the files section for the python code
