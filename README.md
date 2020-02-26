# malaria-docs

## Datasets:  
https://lhncbc.nlm.nih.gov/publication/pub9932

###  Target Product Profile for a mobile app to read rapid diagnostic tests to strengthen infectious disease surveillance  
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6988927/
It is agreed that such a Rapid Diagnostic Test app:
- should be compatible with many Rapid Diagnostic Tests (RDT) and mobile devices without needing accessories
- assist the user with RDT-specific instructions, include checks to facilitate quality control of the testing process
- suggest results with ≥ 95% accuracy across common lighting conditions while allowing the user to determine the final result
- data from the app must be under the control of the health program that operates it
- app should support at least one of the common data exchange formats HL7, FHIR, ASTM or JSON
- this document also lays out the minimum data security and privacy requirements for the app

### Smartphone Dataset
Dataset below contains images taken using a smartphone used in the following paper https://www.researchgate.net/publication/336011001_Deep_Learning_for_Smartphone-based_Malaria_Parasite_Detection_in_Thick_Blood_Smears.

All pictures contain malaria parasites. The positions of the parasites have been documented. Good if we want to use a U-net model.

ftp://lhcftp.nlm.nih.gov/Open-Access-Datasets/Malaria/Thick_Smears_150

### Thin Smear 
https://data.broadinstitute.org/bbbc/BBBC041/

### Articles, healthcare problems in resource-poor settings and solutions using AI

- Title: Transfer Learning for Toxoplasma gondii (parasite) Recognition, URL: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6989130/ Problem: Most current routine diagnostic methods are costly, time-consuming, and labor-intensive Solution: transfer learning-based microscopic image recognition method
- Title: Lymelight: forecasting Lyme disease risk using web search data, URL: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7000681/ Problem: Existing estimates of Lyme disease spread are delayed a year or more Solution: machine-learned classifier of web search sessions
- Title: [Indigenously developed digital handheld Android-based Geographic Information System (GIS)-tagged tablets (TABs) in malaria elimination programme in Mangaluru city, Karnataka, India, URL: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6933888 Solution: Problem: Under-reporting, delayed diagnosis, incomplete treatment and inadequate vector management Solution: digital database of each The ability of vectors such as mosquitos to cover large distances and cross country borders undetected provide an ever-present threat of pathogen spread. malaria case]
- Title: Whole slide imaging system using deep learning-based automated focusing, URL: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6968754/ Problem: auto focusing system, which involves moving a microscope stage along a vertical axis to find an optimal focus position, is the chief component of an automated digital microscope. Current automated focusing algorithms, especially those deployed in cost effective microscopy systems, often cannot match the efficiency of a skilled human operator in keeping a sample in focus Solution: auto focusing system that utilises the recent advances in machine learning, namely deep convolutional neural networks (CNN); (We describe the practical implementation of this method on a low cost digital microscope)
- Title: Using species distribution models to predict potential hot-spots for Rift Valley Fever establishment in the United Kingdom, URL: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6927579/ Problem: The ability of vectors such as mosquitos to cover large distances and cross country borders undetected provide an ever-present threat of pathogen spread Solution: species distribution models to help predict hot-spots for risk of disease establishment; packages available in R: bioclim, multiple generalised linear model (glm), support vector machines (svm), Maximum Entropy (MaxEnt), boosted regression trees (brt) and Random Forest (rf)
- Title: Malaria predictions based on seasonal climate forecasts in South Africa: A time series distributed lag nonlinear model, URL: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6884483/ Problem: Need for early warning system for malaria, using well-organized malaria surveillance and high-quality climate forecasts Solution: weather-based malaria prediction model using a weekly time-series data including temperature, precipitation, and malaria cases from 1998 to 2015 in Vhembe, Limpopo, South Africa and apply it to seasonal climate forecasts
- Title: Prediction mapping of human leptospirosis using ANN, GWR, SVM and GLM approaches, URL: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6854714/ Problem: Modelling and Prediction of Leptospirosis Solution: model and predict the spatial distribution of leptospirosis utilizing Geographically Weighted Regression (GWR), Generalized Linear Model (GLM), Support Vector Machine (SVM) and Artificial Neural Network (ANN) as capable approaches

### A few more apps or similar devices

- Name: NLM  Malaria  Screener Description: for  malaria parasite classification on both thick and thin blood smears; customized CNNmodel  for  parasite  classification Year: 2018 URL: https://cdn.ymaws.com/siim.org/resource/resmgr/mimi18/abstracts/18paper2-Yang.pdf
- Name: Malaria System MicroApp Description: Mobile device based image processing and artificial intelligence techniques as well as a known face detection algorithm to identify Plasmodium parasites Year: 2017 URL: https://www.researchgate.net/publication/316469418_The_Malaria_System_MicroApp_A_New_Mobile_Device-Based_Tool_for_Malaria_Diagnosis
- Name: Matibabu Description: non-invasive method for diagnosing malaria using a mobile application and light sensor; can also test for anaemia, again, non-invasively, no finger prick needed Year: 2017 URL: https://www.springwise.com/mobile-app-uses-light-sensor-diagnose-malaria/
