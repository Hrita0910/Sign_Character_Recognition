# Sign_Character_Recognition

Sign Character Recognition (SCR) is a vital technique that is used to interpret and decipher characters from various sign languages. It analyzes and processes the data from the dataset through machine learning algorithms and computer vision techniques. A sizable collection of data is then used to compile and train the data through a convolutional neural net- work model to extract relevant features like hand gestures
and ultimately give accurate predictions of sign languages. Researchers in diverse domains, such as computer vision, robotics, pattern recognition, machine learning, and sensors,
have shown interest in sign language recognition. The majority of the country’s gesture-based communication relies on how each word is exhibited and punctuated. 

![image](https://github.com/user-attachments/assets/88dbe773-04ff-45e2-8b28-46e827f227cf)

The primary goal is to develop a robust and effective system for sign character recognition, which is important for enhancing communication for dumb and deaf people. Conventional techniques often produce subpar results because they are not able to provide the resilience and accuracy required to recognize a variety of sign characters. First, a large dataset is collected, covering a wide range of sign languages (or hand gestures). Next, the data is processed through techniques like normalization to standardize pixel values for extracting important features. Data augmentation is also performed on the data before creating the model
by generating new data from the original data to increase the overall performance of the model. Using those extracted features, we create a two-dimensional CNN model featuring three Conv2D layers with 32, 64, and 128 filters, pooling layers, and dropout layers, followed by a flatten layer, a hidden layer with 256 neurons, and an output layer. The CNN utilizes several layers, each of which picks up unique characteristics from the input image (sign characters). The model also incorporates the mixed pooling technique, which is a consolidate of max and average pooling to capture the image characteristics. Additionally, a mish activation function is used in place of the conventional ReLU activation function because of its efficiency in training data, which improves the model’s overall accuracy. The aim of this explanation is to
make the process easier to comprehend and carry out. This is followed by a Flatten layer with 256 neurons, all employing Mish activation. This layer performs a reduction operation to generate an output vector representing the number of classes to be predicted. The output layer comprises 25 neurons with softmax activation to provide class probabilities.

Our model achieves a high accuracy of approx. 99%, indicating its effectiveness in correctly classifying instances across all classes. The error rate is very minimal, underscoring the model’s robustness and reliability.

![image](https://github.com/user-attachments/assets/0def356a-fabc-44db-a072-69be1812a043)

