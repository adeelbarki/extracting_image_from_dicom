# extracting_image_from_dicom
## extract the imaging data from each DICOM, visualize it, normalize it, and then visualize only the section of the image that contains the suspicious mass
Python package pydicom is used to extract imaging data from a DICOM file. Looked at images and their intensity distributions before and after normalizing the image's intensity values.

There is a dataframe that contains bounding box coordinates for masses that have been identified by a radiologist in three separate DICOM images. The dataframe gives the starting X & Y coordinates of the bounding box around each mass, and the width and height of the mass. These four values are used to identify the specific rectangular section of each image that contains a suspicious mass.

Extract the imaging data from each DICOM, visualize it, normalize it, and then visualize only the section of the image that contains the suspicious mass. Throughout this process, observing whether or not intensity values are a particularly good characteristic of masses that might help a machine learning algorithm automatically identify them.
