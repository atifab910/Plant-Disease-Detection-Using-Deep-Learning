# Plant-Disease-Detection-Using-Deep-Learning
This project utilizes deep learning (CNN) to classify plant leaves into Healthy, Rust, and Powdery Mildew categories, helping farmers and gardeners detect plant diseases from images
Key Steps:
Data Preprocessing: 
Leaf images are resized, normalized, and augmented for training.
Model Architecture: 
A CNN with convolutional, max-pooling, and fully connected layers for classification.
Training:
The model is trained on augmented data using Adam optimizer and categorical cross-entropy loss.
Prediction:
New images are preprocessed and passed through the classification model.
Output:
Based on the predicted class, relevant messages are generated:
Healthy:
"The plant is healthy. No action needed!"
Rust:
"The plant has rust. Consider fungicide or pruning."
Powdery Mildew:
"The plant has powdery mildew. Treat with fungicide."
Results:
The model accurately classifies leaf diseases and provides actionable insights.

Future Enhancements:
Expand to more diseases.
Deploy as a real-time mobile or web app.
This project offers a scalable solution for plant disease detection, aiding in better crop management
