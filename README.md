# WOMEN-HARRASMENT-PROTECTION-USING-AI
Developed an AI-based offline harassment detection system using audio emotion recognition and video analysis to identify potential threats. Implemented deep learning models with Keras and BiLSTM, and built an interactive interface using Streamlit.


🚨 Offline Harassment Detection
Welcome to Offline Harassment Detection, an AI-powered project designed to detect violent and harassment-related activities in real-time.
This system integrates both audio 🎙️ and video 🎥 models and works without internet connectivity.

✨ Features
Dual-Modality Detection: Combines audio + video analysis for higher accuracy.
Offline Functionality: Works seamlessly without internet connectivity.
Streamlit UI: Clean, simple, and interactive user interface.
Modular Codebase: Separated utilities, models, and UI for scalability.
🛠️ Tech Stack
Programming Language: Python 3.x
Deep Learning Framework: TensorFlow / Keras
Frontend: Streamlit
Datasets:
🎥 RLVS (Violence/Non-Violence video dataset)
🎙️ RAVDESS (Emotional speech dataset for audio classification)
⚙️ Installation & Setup
1. Clone the Repository

git clone https://github.com/purohitharshita/offline-harassment-detection.git
cd offline-harassment-detection
2. Create Virtual Environment

python -m venv myenv
# Activate Virtual Environment
source myenv/bin/activate     # Linux/Mac
myenv\Scripts\activate        # Windows
3. Install Dependencies

pip install -r requirements.txt
4. Run the Application

streamlit run ui.py
📊 Datasets
🎥 RLVS - Real-Life Violence Situations
🎥 RWF-2000 (Alternative Violence Dataset)
🎙️ RAVDESS - Emotional Speech Audio
⚠️ Datasets are not included due to size.
Please download separately and place them inside the data/ folder.
