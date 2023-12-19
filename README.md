# malaria-image-detection
Developing a CNN to detect malaria in microscopic images

The early and accurate detection of malaria is crucial for improving patient outcomes and reducing the severity of the disease. Traditionally, malaria is manually screened by trained healthcare professionals through microscopic examination of blood smears. An automated malaria screener signicantly reduces the time and effort required for manual examination, which is particularly important in resource-constrained regions. This could improve the accuracy and speed of diagnosis, while allowing healthcare facilities to optimize their human resources.

The workflow of this code analysis is:

1. Download the 'cell_images.zip' Zip file from NIH: https://lhncbc.nlm.nih.gov/LHC-research/LHC-projects/image-processing/malaria-datasheet.html
2. Load the files into the working file directory.
3. Run the file 'malaria_image_detection.ipynb' in a Python IDE, which splits both 'Parasitized' (Infected) and 'Uninfected' samples into training, test, and validation classes, and trains the CNN model to detect infection.
