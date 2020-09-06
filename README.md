## Objective
To identify top three diseases that causes elders (age >= 65 yr) to enter hospitals and to locate top three corresponding medications that used for patients with those three common geriatric diseases using NoteEvents file that contains clinical records from MIMIC III database.

## Data
The corpus that is used is MIMIC III (Medical Information Mart for Intensive Care III). MIMIC-III is a large, single-center database comprising information relating to patients admitted to critical care units at a large tertiary care hospital. Data includes vital signs, medications, laboratory measurements, observations and notes charted by care providers, fluid balance, procedure codes, diagnostic codes, imaging reports, hospital length of stay, survival data, and more.

## Methods and Implementation
1) Data prepresessing
2) Getting word frequency on diagnosis notes
3) Using N-Gram to identify diseases
4) Finding word frequencies for filtered patients with certain disease to find top three medications for each disease
5) Using an additional method TFIDF for finding top three medications for each disease

## Results
The top three diseases: Coronary Heart Disease, Hypertension, and Atrial Fibrillation. Corresponding top meditations are: Metoprolol Succinate, Docusate Sodium and Metoprolol Tartrate.

