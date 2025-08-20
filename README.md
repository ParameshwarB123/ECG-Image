🫀 ECG Image Classification Project
📌 Project Overview

This project focuses on classifying ECG (Electrocardiogram) images into different categories using Deep Learning techniques. The aim is to build an automated system that helps in early detection of cardiac-related issues.

📂 Dataset

The dataset consists of ECG image samples classified into the following categories:

Abnormal Heartbeat

History of Myocardial Infarction (MI)

Myocardial Infarction Patients

Normal Persons

Each patient has 12-lead ECG images, and the dataset is organized into class-specific folders.

🛠️ Technologies Used

Python

TensorFlow / Keras or PyTorch (for deep learning)

Flask (for deployment as a web app)

OpenCV & NumPy (for image processing)

⚙️ Model Architecture

We experimented with multiple CNN-based architectures:

Custom CNN with Conv2D, MaxPooling, Dropout layers


RUN
Run your Flask/Django/Streamlit app (app.py)

Most ECG projects use Flask. Try:

python app.py


If Flask is used, you’ll see something like:

 * Running on http://127.0.0.1:5000/
ResNet / VGG16 for transfer learning

Attention-based lightweight CNN
