# 🚨 Offline Harassment Detection  

Welcome to **Offline Harassment Detection**, an AI-powered project designed to detect violent and harassment-related activities in real-time.  
This system integrates both **audio** 🎙️ and **video** 🎥 models and works **without internet connectivity**.  

---

## ✨ Features  

- **Dual-Modality Detection**: Combines audio + video analysis for higher accuracy.  
- **Offline Functionality**: Works seamlessly without internet connectivity.  
- **Streamlit UI**: Clean, simple, and interactive user interface.  
- **Modular Codebase**: Separated utilities, models, and UI for scalability.  

---

## 🛠️ Tech Stack  

- **Programming Language**: Python 3.x  
- **Deep Learning Framework**: TensorFlow / Keras  
- **Frontend**: Streamlit  
- **Datasets**:  
  - 🎥 RLVS (Violence/Non-Violence video dataset)  
  - 🎙️ RAVDESS (Emotional speech dataset for audio classification)  

---

## ⚙️ Installation & Setup  
**1. Clone the Repository**
```bash
git clone https://github.com/purohitharshita/offline-harassment-detection.git
cd offline-harassment-detection

```

**2. Create Virtual Environment**
```bash
python -m venv myenv
# Activate Virtual Environment
source myenv/bin/activate     # Linux/Mac
myenv\Scripts\activate        # Windows

```

**3. Install Dependencies**
```bash
pip install -r requirements.txt
```
**4. Run the Application**
```bash
streamlit run ui.py
```



## 📊 Datasets  

- 🎥 [RLVS - Real-Life Violence Situations](https://www.kaggle.com/datasets/mohamedmustafa/real-life-violence-situations-dataset)  
- 🎥 [RWF-2000 (Alternative Violence Dataset)](https://www.kaggle.com/datasets/vulamnguyen/rwf2000)  
- 🎙️ [RAVDESS - Emotional Speech Audio](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)  

⚠️ Datasets are **not included** due to size.  
Please download separately and place them inside the `data/` folder.




## 📄 License
This project is licensed under the **MIT License**.
