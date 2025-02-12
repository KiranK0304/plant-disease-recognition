# Plant Disease Recognition

## 🌱 Overview
This project is a **Plant Disease Recognition System** that utilizes **Deep Learning** to classify plant diseases based on leaf images. It is built using **TensorFlow** for model training and **Streamlit** for the web-based interface.

## 📂 Project Structure
```
plant-disease-recognition/
│── README.md              # Project documentation
│── requirements.txt       # Dependencies
│── app.py                 # Streamlit main app
│── model/                 # Contains trained model
│   ├── trained_model.keras
│── images/                # Static images for the app and README
│   ├── example_plant.jpg
│── utils/                 # Helper functions (if needed)
│   ├── helper_functions.py
│── dataset/               # Dataset (if needed, or link to external source)
│── .gitignore             # Files to exclude from Git
```

## 🚀 Features
- **Image Upload**: Users can upload an image of a plant leaf.
- **Deep Learning Model**: A pre-trained CNN model predicts plant diseases.
- **Streamlit UI**: A simple and interactive user interface.
- **Fast and Accurate**: Utilizes TensorFlow for quick and precise predictions.

## 📸 Example Usage
![Example Screenshot](images/example_plant.jpg)

## 🛠 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/KiranK0304/plant-disease-recognition.git
cd plant-disease-recognition
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Streamlit App
```bash
streamlit run app.py
```

## 📊 Dataset Information
- This dataset consists of **87K+ images** of **healthy and diseased crop leaves**.
- It contains **38 different classes**.
- It is divided into **train (80%)** and **validation (20%)** sets.
- **Source**: [Plant Village Dataset](https://github.com/spMohanty/PlantVillage-Dataset)

## 🔮 Future Improvements
- Add a **login system** for user authentication.
- Improve model accuracy with more advanced architectures.
- Integrate **explanations** for disease prevention.
- Deploy the project on a **public server** (e.g., Hugging Face or Heroku).

## 📌 License
This project is open-source under the MIT License.

---
**Contributors:** [KiranK0304](https://github.com/KiranK0304) 🎉

