# Kynnovate_2025_SecureX


# Audio and Image Deepfake Detection Projects

## **Overview**
These projects aim to detect deepfakes in audio and image files using machine learning models. The **Audio Deepfake Detection** tool classifies audio clips as real or AI-generated, while the **Image Deepfake Detection** tool identifies deepfake images. Both projects are designed for easy deployment and use.

---

## **Installation Instructions**

### **Step 1: Clone the Repository**
1. Open your terminal or command prompt.
2. Clone the repository using the command:
   ```bash
   git clone <repository_url>
   ```
3. Navigate to the project directory:
   ```bash
   cd <project_directory>
   ```

### **Step 2: Set Up Virtual Environment**
1. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
2. Activate the virtual environment:
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```

### **Step 3: Install Dependencies**
1. Install required libraries by running:
   ```bash
   pip install -r requirements.txt
   ```

### **Step 4: Download Pre-Trained Models**
1. Ensure that the necessary pre-trained models are available:
   - `classifier.pth` for audio detection.
   - `CNN.h5` or `EfficientNet.h5` for image detection.
2. Place these files in their respective directories (e.g., `Saved Models`).

---

## **Running the Projects**

### **Project 1: Audio Deepfake Detection**
1. Start the Streamlit app by running:
   ```bash
   streamlit run <audio_detection_script>.py
   ```
2. Open your browser and navigate to the provided URL (usually `http://localhost:8501`).
3. Upload an audio file (MP3 format).
4. Click "Analyze Audio" to view:
   - The probability score of the audio being AI-generated.
   - A waveform plot for visual analysis.

### **Project 2: Image Deepfake Detection**
1. Start the Flask server by running:
   ```bash
   python app.py
   ```
2. Open your browser and navigate to the provided URL (usually `http://localhost:5000`).
3. Upload an image file.
4. View the classification result indicating whether the image is a deepfake.

---

## **Requirements**
- **Python Version**: 3.8 or higher
- **Key Libraries**:
  - PyTorch
  - Streamlit
  - Flask
  - Librosa
  - Torchaudio
  - Plotly

---

## **Notes**
1. Ensure that all dependencies are correctly installed.
2. For accurate results, verify the format and quality of input files.
3. Modify configurations (e.g., upload size limits) in the respective scripts if needed.

---

## **Contributors**
- Your Name (Optional: add more contributors here).

---

## **License**
Include your project's license details if applicable.

