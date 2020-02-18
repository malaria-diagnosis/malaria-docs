# malaria-docs

datasets: find as many labelled datasets as possible

1. https://lhncbc.nlm.nih.gov/publication/pub9932 
Specifically look at "The datasets are available at cell_images.zip, the codes at malaria_cell_classification_code.zip and the Patient-ID to cell mappings for the parasitized and uninfected classes at patientid_cellmapping_parasitized.csv and patientid_cellmapping_uninfected.csv respectively."

2. https://www.tensorflow.org/datasets/catalog/malaria

Notes: 
- ideally we need the region of interest to be in the center. In practice, might not be the case, the whole image should be considered
- think about picture image size differences: different device = different image size
- would be best to train on data which will look like the image we will get from a photo (ie: not great quality and many cells)
- what is the ratio for which malaria is positive? proportion of parasites
