## Objective
To identify top three diseases that causes elders (age >= 65 yr) to enter hospitals and to locate top three corresponding medications that used for patients with those three common geriatric diseases using NoteEvents file that contains clinical records from MIMIC III database.

## Data
The corpus that is used is MIMIC III (Medical Information Mart for Intensive Care III). MIMIC-III is a large, single-center database comprising information relating to patients admitted to critical care units at a large tertiary care hospital. Data includes vital signs, medications, laboratory measurements, observations and notes charted by care providers, fluid balance, procedure codes, diagnostic codes, imaging reports, hospital length of stay, survival data, and more. The database supports applications including academic and industrial research, quality improvement initiatives, and higher education coursework. It was developed by the MIT Lab for Computational Physiology. It has measurement types, for what the data integration objectives contain demographics, clinical measurement, intervention, billing, medical history Dictionary, pharmacotherapy, clinical laboratory test, and medical data. It also has technology types, for what the data integration objectives contain electronic medical record, medical record, electronic billing system, medical coding process document, and free text format. Compared to other corpora, it has three notable features: it is freely available to researchers worldwide; it encompasses a diverse and very large population of ICU patients; and it contains high temporal resolution data including lab results, electronic documentation, and bedside monitor trends and waveforms. Compared to MIMIC II, its previous version, MIMIC-III is anticipated by its developers to be widely used internationally in areas such as academic and industrial research, quality improvement initiatives, and higher education coursework (Johnson et al., 2016).

## Methods and Implementation
1) Data prepresessing
2) Getting word frequency on diagnosis notes
3) Using N-Gram to identify diseases
4) Finding word frequencies for filtered patients with certain disease to find top three medications for each disease
5) Using an additional method TFIDF for finding top three medications for each disease

## Results
The top three diseases: Coronary Heart Disease, Hypertension, and Atrial Fibrillation. Corresponding top meditations are: Metoprolol Succinate, Docusate Sodium and Metoprolol Tartrate.

