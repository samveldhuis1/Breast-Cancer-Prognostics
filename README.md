# Breast-Cancer-Prognostics
Which patient characteristics best predict recurrence of breast cancer over time?

Population: Breast cancer patients since 1984 being followed-up, and include only those cases exhibiting invasive breast cancer and no evidence of distant metastases at the time of diagnosis.
Predictors: Include 28 features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. A few of the images can be found at
[K. P. Bennett, "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992]
Outcome: Recurrence or nonrecurrene in days.
Horizon: Maximum of 125 days.

After some adjustments such as renaming and checking missingness, the descriptives of the 28 selected variables were observed. 
Part of the variables show skewness to the right. 
We can also see 47 (	23.9%, N = 197	) patients have recurrence of breast cancer. 
The largest proportion of lymph node status was 0 with 87 patients ( 44.2% ), meaning 
axillary and other nearby lymph nodes do not have cancer or only have isolated tumor cells.

A popular prognostic model for predicting breast cancer recurrence is the NPI. The index is calculated using the formula:

NPI = [0.2 x S] + N + G
Where:

S is the size of the index lesion in centimetres
N is the node status: 0 nodes = 1, 1-3 nodes = 2, >3 nodes = 3
G is the grade of tumour: Grade I = 1, Grade II = 2, Grade III = 3
