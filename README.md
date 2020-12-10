# mammoscanner
identify between malignant and benign brain tumors

Using dataset: https://wiki.cancerimagingarchive.net/display/Public/CBIS-DDSM#225166291b3530e3e3034786a37019aba53cafba

Data source comes with each individual patient's .dicom file and a csv for all individuals.
.dicom file has a patient_id attribute that is also found in the csv file which is used to share further information such as pathology (either benign or malignant) pertaining to each specific body part. 

Goal and focus is to label each individually used dicom file to a group (classification) of either malignant or beign of it's respective body parts through the patient_id.

Further plans are to then use the dicom files to make a convolutional neural network that will hopefully allow us to feed new tumor images and determine whether it's benign or malignanat. 
