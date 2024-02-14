# Repository of Breast Cancer imaging dataset

This is the result of an extensive search for open datasets to perform model training during a research assistant position I had in Paris during 2021-2022. While doing this research, it took me a considerable amount of time to gather information on different datasets that were large enough to train deep learning model for breast cancer research that provided useful results.

Thanks to the development of new and more accurate imaging technologies, today, there exist more than 15 different types of breast imaging systems for different image modalities. The following, represent the most frequently used imaging modalities in the medical domain: Full Field Digital Mammography (FFDM), Film Screen Mammography (FSM), Tomosynthesis (3D Mammography), Breast Ultrasound, Breast Magnetic Resonance Image (Breast MRI) [X]. In this project, we focus particularly on FFDM due to it’s extensive worldwide use in clinics and hospitals as it is a very reliable tool for women to obtain a breast cancer diagnosis. This is due to the relative low-cost of an having FFDM, the procedure being less invasive than other methods such as Breast MRI, and  the high-quality scans obtained from this imaging modality. We do however, include a review of a 3D Mammography dataset in this study, as this type of scan is fairly similar to FFDM, yet it yields a higher quality in the resulting scans.

One of the main obstacles in any image-based support system revolves around the access and acquisition of relevant, useful and representative data of the population we are analyzing. There exists different approaches that can be used for detection, sementation, classification and detection of different types of cancer. In particular, breast cancer can profit from a broad range of analytical methods such as: proteomics, histopathology, radiomics and even a combination of several of these methods. Despite the widespread use in research, most of these methods present the challenge of limited access to public data that can be used for developing models and running reliable experiments. In general, the data required for these methods to be reliable is private and an affiliation to a laboratory or medical institute is needed in order to have the necessary clearance due to the sensitivity of the data. In addition, deep learning models require significant amounts of data in order to correctly learn and generalize the representation features that allow the development systems for detection and classification tasks. 

  Open source data has proven very helpful push research forward in many different areas, and in particular in the medical domain with the accessibility to high quality records in a broad range of medical areas. These public datasets are used to train, validate and test many machine learning and deep learning models providing a generalizable benchmark for research groups. Nonetheless, there are few public, standardized and well-curated mammograhy datasets available. 

It is important to consider that in order to develop efficient deep learning models for breast cancer research, the data needs to contain heterogeneous characteristics. It needs to represent a broad range of different characteristics in terms of age, ethnicity and phenotypic characteristics of women considered in the mammography studies. Our goal was not only to find available open source datasets of FFDM studies, but to find datasets collected for different women populations. Up until the writing of this thesis, the open source datasets that we found cover the populations of Africa, Asia, Europe and America. The main reason for this, is to create one large dataset that contains characteristics of all women populations considered. This data could help as a standardized database of FFDM that can help breast cancer researchers to create models that generalize well to the worldwide population of women.

## CBIS-DDSM
This dataset is an updated and standardised subset version of the Digital Database for Screening Mammography (DDSM). The selected images have been decompressed, converted to DICOM format and curated by a trained mammographer.  Updated exact ROI segmentation and bounding boxes are included, as well as pathologic diagnosis for training.  According to our research, this is the most widely used public dataset of mammograms used as a benchmark for breast cancer research.
- American women population (United States)
- Year 2017
- DDSM is a previous version which is considered to be outdated due to the format of images and lack of precision in ROI information
- 753 calcification cases, 891 mass cases

## INBreast
Dataset containing FFDM images acquired at the breast centre located Centro Hospitalar de S. Joao, Porto, Portugal. Several types of lesions (masses, calcifications, asymmetries, and distortions) are included in the imaging characteristics, as well as accurate contours made by specialists. According to our research, this is the second most popular public dataset of mammograms used as a benchmark for breast cancer research.
- European women population (Portugal)
- Year 2012
- ROI and BIRADS assessment information included
- Four different types of lesions recorded in the dataset: masses, calcification, asymmetries, and distortion
- Images are saved in two sizes: 3328x4084 or 2560x3328 pixels in DICOM format

## MIAS
Dataset from the Mammographic Image Analysis Society (MIAS). 322 mammograms obtained and digitised from the UK National Breast Screening Programme. According to our research, this is the third most popular public dataset of mammograms. Despite being outdated, it is continued to be used as a benchmark for breast cancer research.
- European women population (England)
- Year 1994
- ROI is included but not as precise as other datasets

## The Chinese Mammography Database
Dataset consisting of 3,728 mammographies from 1,775 patients from China which present biopsy-confirmed benign or malignant tumors. 1,498 mammographies also include the patients' molecular subtypes. 
- Asian women population (China)
- Year 2016
- No ROI specification or BI-RADS assessment

## King Abdulaziz University Breast Cancer Mammogram Dataset (KAU-BCMD)
Dataset collected from the Sheikh Mohammed Hussein Al-AmoudiCenter of Excellence in Breast Cancer at King Abdulaziz University.  It contains 1416 cases with bilateral views for each breast, annotated and reviewed by three different radiologists. It also contains 205 ultrasound cases corresponding to a part of the mammogram cases, with 405 images as a total.
- Asian women population (Saudi Arabia)
- BIRADS assessment included

## OPTIMAL MAMMOGRAPHY IMAGE DATABASE OMIDB
Dataset created as part of the OPTIMAM project from the UK. Mammograms are obtained from the NHS Screening Programme Dataset. The information regarding this dataset is not completely disclosed as clearance needs to be obtained prior to access to the dataset. The amount of mammograms included seem to surpass the million units.

