# Breast-Cancer-Prediction
### 🚀 **Breast Cancer Prediction**  

A simple yet effective **Machine Learning** project that predicts whether breast cancer is **Malignant (cancerous)** or **Benign (non-cancerous)** using **Logistic Regression**. 🏥💡  

---  

## 🔍 **Project Overview**  
This model is trained on the **Breast Cancer Wisconsin Dataset** (from `sklearn.datasets`) and helps in early detection of breast cancer using **30+ medical features** extracted from digitized tumor images.  

---  

## 📊 **Dataset Details**  
- 📌 **Source:** `sklearn.datasets.load_breast_cancer()`  
- 📌 **Features:** 30 numerical attributes (mean, standard error, and worst values of tumor properties).  
- 📌 **Target Labels:**  
  - `0` → **Malignant (Cancerous)**  
  - `1` → **Benign (Non-cancerous)**  

---

## 🔥 **Machine Learning Model**  
- 🤖 **Algorithm Used:** Logistic Regression  

---

## 💡 **How It Works?**  
1️⃣ **Loads** the dataset 📥  
2️⃣ **Splits** data into training & testing sets 📊  
3️⃣ **Trains** a **Logistic Regression** model 🎯  
4️⃣ **Predicts** whether the tumor is **Malignant or Benign** 🏥  
5️⃣ **Displays results** with accuracy metrics 📢  

---

## 🎯 **Usage Example**  
After training, you can test a new tumor sample using:  
```python
input_data = (17.14,16.4,116,912.7,0.1186,0.2276,0.2229,0.1401,0.304,0.07413,
              1.046,0.976,7.276,111.4,0.008029,0.03799,0.03732,0.02397,0.02308,0.007444,
              22.25,21.4,152.4,1461,0.1545,0.3949,0.3853,0.255,0.4066,0.1059)

prediction = model.predict(np.asarray(input_data).reshape(1, -1))

if prediction[0] == 0:
    print("The Breast Cancer is Malignant")
else:
    print("The Breast Cancer is Benign")
```

---

## 🎯 **Why This Project?**  
✅ **Simple & Beginner-Friendly** – No complex deep learning needed!  
✅ **Fast & Efficient** – Works well with small datasets.  
✅ **Real-World Impact** – Helps in early cancer detection.  

---

## 📜 **License**  
This project is **open-source** and free to use for educational purposes. 🎓  

---

🔥 **Star this repo** if you find it useful! ⭐  
💬 Feel free to share feedback or ask questions!  
