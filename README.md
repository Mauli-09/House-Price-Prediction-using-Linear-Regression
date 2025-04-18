# 🏡 House Price Prediction using Linear Regression

This project builds a simple yet effective **Linear Regression** model to predict house prices based on features like area (square footage), number of bedrooms, and number of bathrooms. It's a great starter project for anyone exploring supervised machine learning and regression analysis.

---

## 🎯 Objective

Use **Linear Regression** to estimate property prices based on key features:
- 📐 Area (Square footage)
- 🛏️ Number of Bedrooms
- 🛁 Number of Bathrooms

---

## 🧠 Workflow

1. 📥 **Load Dataset**  
   - Read housing data from CSV

2. 🧹 **Preprocessing**  
   - Select features: Area, Bedrooms, Bathrooms  
   - Set the target variable: Price

3. ✂️ **Split Data**  
   - Train/Test split (80/20)

4. 🔍 **Train Model**  
   - Fit a `LinearRegression()` model using `scikit-learn`

5. 🧪 **Evaluate Model**  
   - Use metrics like Mean Squared Error (MSE) and R² Score to evaluate performance

---

## 📁 Dataset

- **Filename**: `House Price Prediction Dataset.csv`
- **Format**: CSV
- **Features**:
  - `Area`
  - `Bedrooms`
  - `Bathrooms`
  - `Price` (Target)

---

## 🛠️ Installation

Install the required Python libraries using pip:

```bash
pip install pandas scikit-learn matplotlib

🚀 How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
Place the dataset (House Price Prediction Dataset.csv) in the project folder.

Run the notebook or script:

bash
Copy code
jupyter notebook Prodigy_ML_01.ipynb
📈 Sample Output
text
Copy code
Mean Squared Error: 32124987.12
R-squared: 0.872
The model achieves a high R² score, indicating a strong fit to the data.

📊 Visualization Ideas
Plot predicted vs. actual house prices

Residual plots

Feature importance heatmap

🔮 Future Enhancements
🧠 Use polynomial or ridge regression for improved accuracy

📊 Add more features like location, age of house, amenities

🌐 Build a web app to interact with the model in real-time

👨‍💻 Author
Made with ❤️ by Mauli
📬 Contact: maulikangude007@gmail.com
