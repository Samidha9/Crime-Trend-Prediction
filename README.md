# Crime Trend Predictor 🗽🚔

This [Streamlit](https://crime-trend-prediction.streamlit.app/) web application predicts the **borough** (e.g., Manhattan, Brooklyn) in which a crime likely occurred in New York City, based on key features like offense details, suspect/victim demographics, and jurisdiction.

## 🚀 Features

* Predicts NYC crime borough using a trained **KNN classification model**.
* Interactive UI to input crime-related information.
* Encodes categorical inputs using predefined mappings.
* Provides instant predictions with an easy-to-use sidebar interface.

## 📊 Technologies Used

* Python
* Streamlit
* Pandas
* scikit-learn
* joblib (for model serialization)

## 📁 Project Structure

```
├── knn_model3.pkl          # Trained KNN model
├── streamlit_app.py        # Streamlit application
└── README.md               # Project documentation
```

## 🔧 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/nyc-crime-borough-predictor.git
   cd nyc-crime-borough-predictor
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:

   ```bash
   streamlit run app.py
   ```

## 🧠 Model Info

* **Model Used**: K-Nearest Neighbors (KNN)
* **Input Features**: Encoded values for crime category, jurisdiction, offense type, date, and suspect/victim details.
* **Output**: Predicted NYC borough

## 👥 Team Members

* Ashutosh Panigrahi
* Wanshika Patro
* Samidha Bhosale

---
