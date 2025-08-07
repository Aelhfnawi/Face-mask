😷 Face Mask Detection Using CNN
This project focuses on building a Convolutional Neural Network (CNN) to detect whether a person is wearing a face mask or not. It's a practical example of binary image classification using TensorFlow and Keras.

📁 Dataset
Source: The dataset used contains images of people with and without masks.

Classes:

with_mask

without_mask

Structure: Split into:

Train

Test

Validation

🧠 Model Architecture
Built using Keras Sequential API

Layers used:

Conv2D

MaxPooling2D

Flatten

Dense

Dropout (to prevent overfitting)

Activation: ReLU + Softmax

Loss Function: CategoricalCrossentropy

Optimizer: Adam

Final accuracy: around 97% on validation data

📊 Results
Achieved high accuracy on both training and validation sets.

Performance evaluated using classification reports, confusion matrix, and visual plots.

🖼️ Sample Output
Includes real-time prediction from a webcam (if enabled).

Shows predicted labels on live or static images with bounding boxes.

🚀 How to Run
bash
Copy
Edit
# Clone the repository
git clone https://github.com/YOUR_USERNAME/face-mask-detection.git
cd face-mask-detection

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Face_Mask_Detection.ipynb
📦 Dependencies
TensorFlow

Keras

OpenCV

NumPy

Matplotlib

Make sure you’re using Python 3.7+ and Jupyter Notebook.

🤖 Future Improvements
Add real-time detection using webcam.

Deploy using Flask or Streamlit.

Train with larger, more diverse datasets.

🙌 Credits
Built with ❤️ by Ahmed Elhfnawi
