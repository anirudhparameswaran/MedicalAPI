# MedicalAPI
AI models for medical imaging.

1. Malaria Detection

Files are uploaded in MalariaImaging sub-directory

Steps to run the model

1. Make a new directory malaria inside the MalariaImaging dataset
'''mkdir malaria
   cd malaria'''

2. Download the dataset using the following code
'''wget https://ceb.nlm.nih.gov/proj/malaria/cell_images.zip
   unzip cell_images.zip'''
   
3. Change directory back into the MalariaImaging subdirectory and run build_dataset.py
'''python3 build_dataset.py'''

4. Now run the train_model
