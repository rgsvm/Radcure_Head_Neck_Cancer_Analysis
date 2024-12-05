# Radcure_Head_Neck_Cancer_Analysis

# Models : 
1. LogisticRegression
2. Lasso
3. RandomForestClassifier
4. SVM
5. Naive Bayes

# DataSet Description:

The RADCURE dataset was collected clinically for radiation therapy treatment planning and retrospectively reconstructed for quantitative imaging research.

Inclusion: The dataset used for this study consists of 3,346 head and neck cancer CT image volumes collected from 2005-2017 treated with definitive RT at the University Health Network (UHN) in Toronto, Canada

Acquisition and Validation Methods: RADCURE contains computed tomography (CT) images with corresponding normal and non-normal tissue contours. CT scans were collected using systems from three different manufacturers. Standard clinical imaging protocols were followed, and contours were generated and reviewed at weekly quality assurance rounds. RADCURE imaging and structure set data was extracted from our institution’s radiation treatment planning and oncology systems using an in-house data mining and processing system. Furthermore, images are linked to clinical data for each patient and include demographic, clinical and treatment information based on the 7th edition TNM staging system. The median patient age is 63, with the final dataset including 80% males. Oropharyngeal cancer makes up 50% of the population with larynx, nasopharynx, and hypopharynx cancer, comprising 25, 12, and 5% respectively. Median follow-up was 5 years with 60% of the patients alive at last follow-up.

Data Format and Usage Notes: During extraction of images and contours from our institution’s radiation treatment planning and oncology systems, the data was converted to DICOM and RTSTRUCT formats, respectively. To improve the usability of the RTSTRUCT files, individual contour names were standardized for primary tumor volumes and 19 organs-at-risk. Demographic, clinical, and treatment information is provided as a comma-separated values (csv) file. This dataset is a superset of the Radiomic Biomarkers in Oropharyngeal Carcinoma (OPC-Radiomics) dataset and fully encapsulates all previous data; this dataset replaces the OPC-Radiomics dataset. The RTSTRUCTs from OPC-Radiomics have been standardized to adhere to the TG263 nomenclature. Age of 90 years or greater is considered PHI and set to 90 years to minimize impact to privacy. Both radiological and clinical metadata were offset by an undisclosed number of days for anonymization and should be noted for downstream analysis. The TG263-standardized RTSTRUCTs include only the GTVp (primary gross tumor volume) contours. Patients without corresponding GTVp contours will not have RTSTRUCTs.

Potential Applications: The availability of imaging, clinical, demographic and treatment data in RADCURE makes it a viable option for a variety of quantitative image analysis research initiatives. This includes the application of machine learning or artificial intelligence methods to expedite routine clinical practices, discover new non-invasive biomarkers, or develop prognostic models.

🟩Data Citation
Welch, M. L., Kim, S., Hope, A., Huang, S. H., Lu, Z., Marsilla, J., Kazmierski, M., Rey-McIntyre, K., Patel, T., O’Sullivan, B., Waldron, J., Kwan, J., Su, J., Soltan Ghoraie, L., Chan, H. B., Yip, K., Giuliani, M., Princess Margaret Head And Neck Site Group, Bratman, S., Haibe-Kains, B., Tadic, T. (2023). Computed Tomography Images from Large Head and Neck Cohort (RADCURE) . The Cancer Imaging Archive. https://doi.org/10.7937/J47W-NM11
