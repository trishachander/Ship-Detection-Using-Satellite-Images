# Airbus-Ship-Detection

Report Assignment:

Submit a report with the proposal for your term project. The report should contain the following:

Scope & task

Data flow diagram – high level

Features to be used

Algorithms to be used for classification, clustering or prediction tasks

Tentative plan with expected outcomes from this project

Scope and Task: This project is a solution for the challenge made by AIRBUS (AIRBUS-Ship-Detection-Challenge). The project is aimed to enhance the monitoring of the ship traffic to reduce ship accidents, illegal fishing, drug trafficking, and illegal cargo movement. The key objective of this project is to identify the ships in a particular aerial image of sea routes.

There are some constraints applied while developing this project as the input data is considered to of the area far away from sea shores, thus it does not show any land. Model may identify the ships in such aerial images but the accuracy might be low. The condition of extremely dense clouds is also excluded as in that case, the ships won't be detected.

Data Flow Diagram:

NOTE: The data that we took is unlabeled, so we have to manually classify it.

Features to be used:

The feature vectors that are planned to use are: -

Mean Pixel Value [1] - Calculation of mean of R, G and B values of every pixel, reducing from 3 layer to 1 layer.

Otsu threshold masking [2] - Calculating a threshold for every image and assigning 0, 255 for every pixel if greater/less than threshold respectively.

Hu Moments [3] - Used to characterize the shape of the ships in an image.

Algorithms for prediction:

Deep learning model: CNN / Transfer Learning - U-Net [4], Mask R-CNN [5]

References: 
[1]: #Method 2 in https://www.analyticsvidhya.com/blog/2019/08/3-techniques-extract-features-from-image-data-machine-learning-python/ 
[2]: https://en.wikipedia.org/wiki/Otsu%27s_method 
[3]: https://cvexplained.wordpress.com/2020/07/21/10-4-hu-moments/ 
[4]: https://paperswithcode.com/method/u-net [5]: https://viso.ai/deep-learning/mask-r-cnn/#:~:text=Mask%20R%2DCNN%20is%20a,segmentation%20mask%20for%20each%20instance.&text=Region%2DBased%20Convolutional%20Neural%20Networks%20(R%2DCNN)
