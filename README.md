# Numerical Digits Recognition

Numerical Digits Recognition is a digit recognition project that aims to accurately recognize hand-drawn numerical digits. The purpose of this project is to provide a practical solution for optical character recognition, object detection, and other applications that require automatic digit recognition. The project utilizes machine learning algorithms to achieve high accuracy and robustness.

## Installation:
1. Clone the repository: `git clone https://github.com/Hassouna9/Digit-Recognition`
2. Set up the project environment and configuration.

## Usage:
1. Prepare your digit images for recognition.
2. Use the provided functions to process and classify the digit images.
3. evaluate the accuracy of the recognition results.

## Dataset:
The project uses the MNIST dataset, which consists of 60,000 training images and 10,000 test images of hand-drawn numerical digits. The dataset provides a realistic representation of handwritten digits encountered in real-world scenarios. Preprocessing steps, such as normalization and resizing, are applied to the dataset to ensure consistency and optimal performance during training and testing.

You can find the dataset on this link `https://drive.google.com/drive/folders/1j8EVjz4r1ZVEs4YatT0-ZcWw-oKTYHBq?usp=sharing` , install it and create a new folder 'data' in the project directory.

## Model:
The digit recognition model in this project is based on the K-Nearest Neighbors (KNN) algorithm. KNN is a supervised machine learning algorithm known for its simplicity and efficiency in classification tasks. The model is trained using the MNIST dataset and tuned with appropriate parameters to achieve accurate digit recognition.

## Results:

### Performance Comparison:
We compared the performance of the Numerical Digits Recognizer using two distance metrics: Manhattan distance and Euclidean distance. The algorithm was tested on a subset of the dataset, consisting of 30,000 training images and 5,000 test images. The results are summarized in the following table:

| Distance Metric   | Accuracy    | Runtime (in seconds) |
|-------------------|-------------|----------------------|
| Manhattan         | 94%         | 23.5                 |
| Euclidean         | 95%         | 25.1                 |

Based on the results, we observed that both distance metrics achieved high accuracy levels. The Euclidean distance metric slightly outperformed the Manhattan distance metric by 1%. However, it's important to note that the Manhattan distance metric yielded results in a slightly shorter runtime compared to the Euclidean distance metric.

### Recognition Speed:
In addition to accuracy and runtime, we measured the recognition speed of the Numerical Digits Recognizer. We found that the algorithm was able to recognize an image in just 300 milliseconds. This fast recognition speed enables efficient real-time classification of hand-drawn numerical digits.

Furthermore, the recognition accuracy achieved by the algorithm was 92%, indicating that the majority of the recognized digits matched the ground truth labels. This level of accuracy demonstrates the effectiveness of the Numerical Digits Recognizer in accurately identifying and classifying hand-drawn numerical digits.


## Limitations and Future Improvements:
- The current model may struggle with highly distorted or poorly drawn digits. Further improvements can be made to handle such cases more effectively.
- Exploring other machine learning algorithms, such as convolutional neural networks (CNNs), can potentially improve recognition accuracy further.
- Integration with a user-friendly graphical interface can enhance the usability and accessibility of the project.

## Contributors:
- Ahmed Ashraf Hamed 
- Omar Khaled Abu El Fetoh 
- Mohamed Mostafa Motawie

Contact Information:
For any questions or feedback, please contact us at [ahmedashraf.aa02@gmail.com].
