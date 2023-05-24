# fluffy-disco

The convolutional neural network (CNN) is a powerful deep learning model used for image classification tasks, and in this case, it is applied to the HAM10000 dataset provided by Harvard Medical School. This dataset consists of 10015 dermatoscopic images, each representing a skin lesion belonging to one of seven different classes. The dataset is clean, organized, and specifically designed for building machine learning models.

One notable aspect of the dataset is the presence of imbalanced classes, where there are sharp differences in the number of images available. Also, present in some images are vignettes, medical equipment, and other disruptive elements. These features can significantly impact the classification performance of a model.

The goal of the CNN approach is to accurately classify skin lesions, which requires distinguishing between fine-grained categories. Dermatologists are only able to visually identify skin lesions 46% ~ 54% of the time. By training a single CNN using only image pixels and labels as inputs, our approach achieves comparable performance to state-of-the-art models.

Overall, the CNN model applied to the HAM10000 dataset demonstrates the effectiveness of deep learning in image classification tasks, specifically for identifying and classifying skin lesions. It showcases the potential for leveraging advanced machine learning techniques to improve diagnostic accuracy in dermatology.
