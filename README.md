# 📈 Sales Forecasting with Linear Regression

This project demonstrates how to forecast sales based on advertisement budgets using **Linear Regression**, complete with data analysis, model evaluation, and a **frontend interface** for live predictions.

---

## 🎯 Objective

To predict the `Sales` of a House in future based on the amount spent on:
- Bed Rooms
- Bath rooms
- area size
- Other Features

---

## 🧰 Tools & Technologies

| Category        | Tools / Libraries                         |
|-----------------|--------------------------------------------|
| Language        | Python 3.x                                 |
| Data Handling   | pandas, numpy                              |
| Visualization   | seaborn, matplotlib                        |
| Modeling        | scikit-learn (LinearRegression)            |
| Interface       | HTML,CSS                                  |
                                   

---

## 📊 Dataset Description

We used the classic **Housing.csv** dataset.

---

## 🔍 Project Steps

1. **Data Import & Exploration**
   - Checked for nulls and basic stats
   - Visualized correlation using heatmaps and scatter plots

2. **Model Training**
   - Used `LinearRegression()` from `scikit-learn`
   - Split dataset into train/test sets

3. **Model Evaluation**
   - Evaluated model with:
     - R² Score
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)

4. **Web Interface**
   - Created a user-friendly input form to get sales predictions
   - Integrated the trained model for live demo

---

## 📈 Sample Prediction

```python
Input:
rooms = 3  
bathrooms = 2 
kitchen= 1 
Other Features

Output:
Predicted Sales = 17.45(just raw value)
```

---

## 🖼️ Interface Screenshot


![Sales Forecasting Output](https://raw.githubusercontent.com/FaryalNimra/SalesPredictionSystem/master/Sales_Forecasting.png)


---

## 📚 Requirements

Install required libraries using:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn joblib
```

---

## 💻 How to Run

```bash
python app.py
```

This will launch the web app in your browser.

---

## 📈 Results

| Metric | Score      |
|--------|------------|
| R²     | 0.897      |
| MAE    | ~1.2       |
| MSE    | ~2.5       |

---

## 👩‍💻 Author

**Faryal Nimra**  
📧 [faryalnimra190@gmail.com](mailto:faryalnimra190@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/faryal-nimra-4a49a32b6)  
🌐 [Portfolio](https://portfolio-five-beige-ixn8l41et7.vercel.app/)

---

## 🚀 Future Enhancements

- Add more ML models (Ridge, Lasso, RandomForest)
- Deploy on platforms like Hugging Face, Streamlit Cloud


