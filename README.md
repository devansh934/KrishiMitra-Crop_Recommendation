# 🌾 **KrishiMitra: Crop Recommender**

**KrishiMitra** is a precision agriculture tool built using **Streamlit** to support farmers in making accurate, data-driven crop selection decisions. Agriculture today demands intelligent solutions—mistakes in crop planning can lead to resource wastage and economic loss. KrishiMitra addresses this by offering recommendations grounded in environmental and soil data, empowering farmers to farm smarter.

---

## 🎯 Project Goals

KrishiMitra is designed to contribute toward sustainable and efficient farming practices. Its core objectives are:

- 🌱 Increase agricultural productivity through intelligent crop planning  
- 🌾 Minimize chemical usage by recommending crops that suit the soil's natural nutrient profile  
- 💧 Improve water resource efficiency by aligning crop choices with water requirements  
- 🛡️ Preserve soil health by avoiding overexploitation and degradation of the land

---

## 🧠 How It Works

The application takes in key agricultural parameters such as:

- Soil nutrient levels (Nitrogen, Phosphorus, Potassium)  
- pH of the soil  
- Rainfall  
- Humidity  
- Temperature  

Using this input, **KrishiMitra** recommends the most suitable crop to cultivate using a **machine learning model** trained on real-world agricultural data.

---

## 📂 Dataset Used

The model behind KrishiMitra is trained on a curated dataset sourced from Kaggle:  
🔗 [Crop Recommendation Dataset – Kaggle](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)

---

## 📸 Demo

Here’s what the application looks like:

![cropImg1](https://github.com/user-attachments/assets/a46099f8-ba9d-49ea-b670-0c4d11eee5d7)
![cropImg](https://github.com/user-attachments/assets/fb9812aa-65f0-4b30-b229-151e63e6fccc)




> 📌 Replace `demo-screenshot.png` with your actual screenshot file.

---

## 🧰 Tech Stack

- **Python**
- **Pandas**, **NumPy**, **Scikit-learn** – for data processing & ML
- **Streamlit** – for the interactive web app interface
- **Matplotlib/Seaborn** *(optional)* – for data visualization

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/devansh934/KrishiMitra-Crop_Recommendation.git
cd crop-webapp
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App

```bash
streamlit run crop-webapp.py
```

### 4. Open in Your Browser

Usually available at: [http://localhost:8501](http://localhost:8501)
