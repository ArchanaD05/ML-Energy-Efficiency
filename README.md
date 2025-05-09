# 🏡 Energy Efficiency Modeling with Machine Learning 💡

Welcome to my repository! This project is all about using **Machine Learning** to predict how much energy buildings need for **heating and cooling**. 🌡️ We explored several models to see which ones are best for helping design smarter, greener buildings. 🌿

---

## 📊 About the Dataset

The dataset includes **768 building samples**, each with:
- 8 input features (X1 to X8) like:
  - 🧱 Relative Compactness
  - 🧱 Surface Area, Wall Area, Roof Area
  - 📏 Overall Height
  - 🧭 Orientation (North, South, etc.)
  - 🪟 Glazing Area & Glazing Distribution
- 2 output variables:
  - 🔥 Heating Load (Y1)
  - ❄️ Cooling Load (Y2)

📁 Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Energy+efficiency)

---

## 🚀 What I Did

We explored the dataset using:
- 📈 **Histograms, Correlation Analysis**
- 📉 **Descriptive Stats, Linear Regression**
- 🧮 **VIF Analysis** to reduce multicollinearity

Then we trained several **ML models**:
- ✅ Perceptron (💯 Best Accuracy: Y1 – 97.65%, Y2 – 98.17%)
- 🔍 Support Vector Machines (Y1 – 84.8%, Y2 – 87.4%)
- 🧠 Neural Networks (Y1 – 96.48%, Y2 – 95.14%)
- 📦 K-Nearest Neighbors
- 🔮 Naïve Bayes

I also categorized loads using **quartiles** and evaluated classification performance.

---

## 🧠 Insights

- **Neural Networks** and **Perceptron** models gave the most accurate results.
- Features like **Wall Area**, **Roof Area**, and **Glazing Area** had major impacts on energy use.
- Certain designs save more energy depending on **orientation and glass distribution**.
- These insights can help architects and builders create **more energy-efficient homes**!

---

## 📚 Tools Used

- Python (Pandas, Sklearn, NumPy, Matplotlib)
- Excel
- PowerPoint
- Scikit-learn ML algorithms

---

## ⭐️ Fun Fact

Machine Learning isn’t just for Netflix and finance — it can help **save the planet** one building at a time! 🌍💪


