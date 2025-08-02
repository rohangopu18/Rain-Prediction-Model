##  Rainfall Prediction 
A machine learning classification project to predict whether it will rain today in Melbourne, Australia, using historical weather data.

##  Author
Rohan Gopu

## Project Objective
The goal of this project is to accurately predict whether it will rain today based on weather features like temperature, humidity, wind direction, and more. This can help in better planning for agriculture, transportation, and daily life.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Project Structure
rainfall-prediction/
│
├── data/ # Raw & cleaned datasets (not uploaded for privacy)
├── notebook.ipynb # Main project notebook
├── README.md # Project overview
└── results/ # Confusion matrix, feature importance plots

##  Setup Instructions

1. Clone the repository  
git clone https://github.com/your-username/rainfall-prediction.git
cd rainfall-prediction

markdown
Copy
Edit

2. Install dependencies  
pip install -r requirements.txt

mathematica
Copy
Edit

3. Launch Jupyter Notebook  
jupyter notebook

markdown
Copy
Edit

4. Open `notebook.ipynb` and run all cells.

## Models Used

- **Random Forest Classifier**
- Accuracy: ~85–87%
- True Positive Rate: Higher
- **Logistic Regression**
- Accuracy: ~83%
- More interpretable model, but lower recall for rain

## Key Insights

- The dataset is **imbalanced**: It rains less frequently.
- **Top Features**: `Humidity3pm`, `Rainfall`, `Pressure9am`, etc.
- **Random Forest** outperforms Logistic Regression on this dataset.

## Future Improvements

- Try other models (XGBoost, SVM, etc.)
- Tune hyperparameters more extensively
- Handle missing values differently
- Engineer additional weather-based features
- Apply SMOTE or other balancing techniques

## Results Visuals

- Feature importance bar chart
- Confusion matrix heatmap
- Classification reports for each model

## License

This project is for educational purposes only..

Feel free to fork or start the repo. Contributions are welcome!
