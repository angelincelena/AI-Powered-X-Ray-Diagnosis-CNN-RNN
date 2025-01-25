🩻 AI-Powered X-Ray Diagnosis Using CNN + RNN
This project combines Convolutional Neural Networks (CNNs) for feature extraction and Recurrent Neural Networks (RNNs) for text generation, enabling automated X-ray disease diagnosis. It employs Grad-CAM for visual interpretability and Gradio for an interactive web-based interface.

🚀 Features
✅ Upload X-ray images for disease detection
✅ Uses EfficientNetB0 (CNN) for feature extraction
✅ Uses LSTM (RNN) to generate medical impressions
✅ Implements Grad-CAM to visualize model attention
✅ Provides disease prediction with bounding boxes
✅ Interactive Gradio UI for easy testing

📂 Dataset
This project uses the Indiana University Chest X-ray Dataset, which contains paired X-ray images and radiology reports.

🔗 Download Dataset:
Kaggle - Chest X-rays Indiana University

To use this dataset, follow these steps:

bash
Copy
Edit
!kaggle datasets download -d raddar/chest-xrays-indiana-university
!unzip chest-xrays-indiana-university.zip -d chest_xray_data
🛠 Installation
Clone the repository and install the dependencies:

bash
Copy
Edit
git clone https://github.com/your-username/AI-Xray-Diagnosis.git
cd AI-Xray-Diagnosis
pip install -r requirements.txt
📜 Usage
Run the Project
bash
Copy
Edit
python app.py
OR, if using Google Colab:

python
Copy
Edit
!pip install gradio
Then execute the notebook.

Run the Gradio Interface
After running the script, Gradio will generate a public link:

csharp
Copy
Edit
Running on public URL: https://xyz.gradio.live
Click the link to interact with the model.

🔍 Model Architecture
The system consists of:

Feature Extraction (CNN) - Extracts deep X-ray features
Disease Classification - Predicts potential lung diseases
Grad-CAM - Highlights important regions in the X-ray
Caption Generation (RNN) - Generates medical impressions
Superimposed Output - Displays Grad-CAM heatmap
Results Display - Shows predicted disease + caption
🎯 Results & Evaluation
📊 Evaluation Metrics:
✅ Accuracy (CNN Disease Classification)
✅ BLEU Score (RNN Captioning)
✅ Grad-CAM Visual Explainability

🖼 Example Output
Original X-ray
Grad-CAM Heatmap (Model’s Focus)
Superimposed X-ray (Highlighting Disease)
Prediction Status (e.g., Pneumonia Detected ⚠️)
Generated Medical Report
🤝 Contributors
Your Name - AI & ML Developer
Want to contribute? Feel free to fork and submit a PR!

📜 License
This project is open-source under the MIT License.

🛠 Future Enhancements
🔹 Improve accuracy with pre-trained transformers
🔹 Deploy as a real-time web app
🔹 Add multi-class disease detection
🔹 Implement GANs for X-ray augmentation

