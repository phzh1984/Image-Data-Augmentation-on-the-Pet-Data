# Image-Data-Augmentation-on-the-Pet-Data

This project incorporates image data augmentation techniques to enhance the training dataset. Techniques like rotation, flipping, scaling, and color manipulation are utilized to augment the dataset, improving model generalization and performance.

Dataset Description

Training Data

train/: Contains training set photos in the format {id}.jpg, where {id} represents a unique Pet Profile ID.

train.csv: Metadata for each training photo, including the target variable - the photo's Pawpularity score. The 'Id' column corresponds to the unique Pet Profile ID matching the photo's file name.

Example Test Data

test/: Comprises randomly generated images similar to the training set photos. The actual test data includes approximately 6800 pet photos resembling the training set.

test.csv: Metadata similar to the training set's metadata.

