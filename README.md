# Assessing-Image-Filter-Effectiveness-A-Comparative-Study-with-Noise-Injection-and-Data-Augmentation
Research investigates the impact of data augmentation and noise injection on image filtering techniques for static image denoising and recognition tasks using the MNIST dataset, evaluating various filters and measuring performance with PSNR and NMSE.

## About the dataset
The MNIST Handwritten Digit Dataset is a widely used benchmark dataset in the field of machine learning and computer vision. It consists of 70,000 grayscale images of handwritten digits (0-9), with 60,000 images used for training and 10,000 for testing. Each image is a 28x28 pixel square, making it a popular choice for tasks such as digit recognition and image classification.

link- http://yann.lecun.com/exdb/mnist/

## Methodology
### A. Import and Preprocess the MNIST Dataset
The initial phase of the research involves importing the MNIST dataset, which comprises handwritten digit images. This dataset is widely used in the field of machine learning and computer vision for tasks such as digit recognition. To prepare the dataset for further analysis, meticulous preprocessing steps are undertaken. These steps include techniques such as edge detection, image cleaning, and one-hot encoding. Edge detection helps in identifying the boundaries of objects within the images, which can be crucial for subsequent filtering and enhancement processes. Image cleaning techniques are employed to remove any unwanted artifacts or noise that might be present in the dataset. Finally, one-hot encoding is applied to ensure that the labels associated with each image are properly encoded for use in machine learning algorithms.

### B. Application of Image Filtering Techniques
Once the MNIST dataset is prepared, nine diverse filtering techniques are systematically applied to each image. These filtering techniques encompass a range of approaches including mean filtering, median filtering, Gaussian filtering, box blur filtering, Canny edge filtering, spatial filtering, temporal filtering, Mexican hat filtering, and bilateral filtering. Each filter operates differently and has its own strengths and weaknesses in terms of noise reduction and image enhancement. The primary objective in this phase is to assess the individual accuracy of each filter in enhancing image quality and suppressing noise.

### C. Data Augmentation for Enhanced Accuracy
Recognizing the importance of data augmentation in improving image classification accuracy, this critical step is introduced into the research. Data augmentation involves applying a series of transformations and manipulations to the dataset to diversify its contents. These augmentations aim to simulate real-world variations and challenges that image recognition systems might encounter. By introducing variations such as rotation, scaling, and translation to the images, the dataset becomes more robust, thereby improving the performance of the image recognition model.

### D. Injection of Noise for Real-World Simulations
To provide a more comprehensive evaluation, various types of noise are introduced into the filtered images. These types of noise include salt and pepper noise, speckle noise, Gaussian noise, and Poisson noise, which are commonly encountered in real-world scenarios. By injecting noise into the filtered images, the research aims to simulate the challenges posed by noise in real-world applications. The Noise Mean Squared Error (NMSE) and Peak Signal-to-Noise Ratio (PSNR) are meticulously measured for each filter when exposed to these different types of noise. This allows for a thorough understanding of how each filter performs in the presence of real-world noise.

### E. Visualizations of PSNR and NMSE Scores
The research culminates in the visualization of the NMSE and PSNR scores for each filtering technique. Two distinct graphs are generated for each filter, one depicting NMSE scores and the other PSNR scores. These graphs offer a comprehensive comparative analysis, shedding light on how each filter fares in terms of noise reduction and signal fidelity under different conditions. The visualizations allow for a clear assessment of the strengths and weaknesses of each filtering technique, providing valuable insights for further research and practical applications.

Through these meticulously planned steps, the research aims to provide a holistic and practical understanding of the performance of various filtering techniques on static images, considering the real-world challenges posed by noise and the benefits brought about by data augmentation.
