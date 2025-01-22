# Artrya Demographics Assessment

## Project Overview
This project explores the significance of demographic categories in relation to CAD (coronary artery disease) diagnosis. It highlights how finer details in demographics can enhance the classification of subjects, offering deeper insights into the disease.

## Dataset
The analysis utilizes multiple data sources:
- **Primary Dataset**: A JSON file named `Artrya_primary_dataset.json`, containing demographic and clinical data relevant to CAD diagnosis.
- **Inclusion and Exclusion Criteria**: Two Excel files, `inclusions.xlsx` and `exclusions.xlsx`, are used to manipulate and filter the primary dataset based on specific study criteria.

## Key Findings
The current demographic details within the dataset are not sufficiently granular for optimal classification. By delving deeper into the demographics, we can refine them to a more granular level. This would enhance the understanding and classification of individuals with the disease.

## Insights on Demographic Data Collection
If designing a study to collect race and ethnicity data in detailed form, it is crucial to consider both the scientific objectives and the social and cultural contexts of the study population. A detailed and culturally sensitive approach to collecting race and ethnicity data is recommended. This approach should include:

- Detailed subject self-identification.
- Additional options such as "other" for flexibility.
- Expansion of sub-options for various ethnic groups, such as:
  - Asian: Chinese, Indian, Filipino, Vietnamese, Korean, Japanese, etc.
  - Hispanic or Latino: Mexican, Puerto Rican, Cuban, Salvadoran, Dominican, etc.
  - African: Nigerian, Ethiopian, Somali, Ghanaian, etc.
  - Middle Eastern or North African: Egyptian, Iranian, Syrian, Lebanese, etc.

By implementing such a detailed approach, the study can achieve a more nuanced understanding of health disparities, cultural influences, and social determinants of health. This careful categorization can ultimately lead to more targeted and effective interventions.

## Project Structure
- `notebooks/`: Contains the Jupyter Notebook with the analysis.
- `data/`: Includes the dataset JSON file and the inclusion/exclusion Excel files.
- `images/`: Contains visualizations and plots.

## Running Instructions
To run the notebook, ensure the following dependencies are installed:
- Python 3.x
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib
- Openpyxl (for reading Excel files)

After installing the dependencies, navigate to the `notebooks/` directory and run the Jupyter Notebook.

## Author
Fabian Msafiri
