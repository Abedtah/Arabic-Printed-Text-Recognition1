# Arabic-Printed-Text-Recognition
This project adapts an existing Arabic handwritten text recognition model to accurately recognize printed Arabic script. Originally designed for handwriting, we retrained the model on a new dataset of printed line images, achieving strong recognition performance.

🚀 What We Built
Model Fine-Tuning:
Fine-tuned a deep learning model combining Convolutional Neural Networks (CNN), Bidirectional RNNs (BiRNN), and CTC (Connectionist Temporal Classification) decoding.

Preprocessing Pipeline:
Developed a full preprocessing system including:

Grayscale normalization

Image resizing

Right-to-left text alignment

Data Preparation:
Converted raw printed Arabic line images into HDF5 datasets to optimize training and prediction workflows.

Batch Inference System:
Designed a system to process batches of line images and reconstruct full pages of recognized Arabic text.

🛠️ Tech Stack
TensorFlow

Python

OpenCV

HDF5

NumPy

📚 Skills Gained
Model retraining and fine-tuning for domain adaptation

Handling challenges unique to Arabic OCR (e.g., right-to-left text, ligatures)

Dataset preparation and optimization

Building robust preprocessing and inference pipelines

👥 Team
Abed Taha

Ahmad Saker

Mohammad Ganayem


📂 How to Use
Clone the repository:

git clone https://github.com/Abedtah/Arabic-Printed-Text-Recognition.git

Set up your environment:

pip install -r requirements.txt

Prepare your dataset (convert to HDF5 format using provided scripts).

Train or run inference using the model!
