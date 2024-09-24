Music Genre Classification
This project aims to classify music genres using deep learning techniques. The dataset utilized is the GTZAN dataset, which comprises ten genres with 100 audio files each. For this project, the dataset is divided into two folders: a training set with 10 genres (80 files each) and a testing set with 200 audio files of mixed genres.

Technologies Used
Python: The primary programming language for development.
Librosa: For audio processing and feature extraction.
TensorFlow: For building and training the deep learning model.
NumPy: For numerical computations.
Matplotlib: For visualizing the data.

Key Features:

Data Preprocessing: The audio files are processed using Librosa to extract Mel spectrograms, which visually represent audio signals. Each spectrogram is resized to a uniform size of 128x128 pixels, ensuring consistent input for the model.

Model Architecture: A CNN model is built using TensorFlow and Keras, incorporating layers such as Conv2D, MaxPooling2D, Flatten, and Dense. This architecture is designed to effectively learn features from the Mel spectrograms, allowing for accurate genre classification.

Training and Evaluation: The model is trained on the training dataset, and its performance is evaluated using accuracy metrics. The dataset is split into training and validation sets to monitor the model’s learning process.

Genre Prediction: A prediction function is implemented to classify new audio files based on the trained model. The predicted genres are returned in an easily interpretable format.

This project serves as an introduction to applying deep learning techniques in audio classification and showcases the effectiveness of CNNs in recognizing patterns in audio data. Future work could explore model optimization, the inclusion of additional features, and experimenting with different neural network architectures for improved accuracy.
