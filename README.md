# Churn Analysis


Welcome to the Churn Analysis project! This repository provides an end-to-end pipeline for predicting customer churn using Artificial Neural Networks (ANN) and Simple RNN architectures. The project is implemented in Python using Jupyter Notebooks and Streamlit for interactive UI.

---

## 🚀 Features

- **Data Preprocessing & Feature Engineering**
- **Model Building (ANN, RNN)**
- **TensorBoard Integration for Experiment Tracking**
- **Model Serialization for Easy Deployment**
- **Interactive Prediction and Visualization with Streamlit**
- **Easy Environment Setup with Conda**

---

## 🛠️ Tools, Libraries & IDEs Used

| Tool/Library        | Purpose                                 |
|---------------------|-----------------------------------------|
| **Python 3.11**     | Main programming language               |
| **Jupyter Notebook**| Interactive coding, experimentation     |
| **TensorFlow/Keras**| Deep learning (ANN, RNN models)         |
| **Pandas**          | Data manipulation and analysis          |
| **NumPy**           | Numerical computations                  |
| **Matplotlib**      | Data visualization                      |
| **Scikit-learn**    | Preprocessing, metrics                  |
| **Streamlit**       | Building interactive web UI             |
| **TensorBoard**     | Visualize training logs and metrics     |
| **Pickle**          | Model & feature serialization           |
| **Conda**           | Environment management                  |

> **IDE Used:**  
> - **Jupyter Notebook** (recommended for experimentation)
> - **Visual Studio Code** (for Python and Streamlit app development)

---

## 📦 Installation & Setup

```bash
# 1. Create environment
conda create -p venv python=3.11 -y

# 2. Activate environment
conda activate venv/

# 3. Install requirements
pip install -r requirements.txt
```

---

## 🧑‍💻 Usage

1. **Build & Train Model:**  
   - Run `experiments.ipynb` or `Simple RNN/implementation.ipynb` for model training and feature engineering.
   - Training logs and metrics are saved for TensorBoard visualization.

2. **View TensorBoard:**  
   - Launch TensorBoard to visualize training:
     ```
     %tensorboard --logdir logs/fit20250328-112924
     ```

3. **Prediction:**  
   - Use `prediction.ipynb` to run predictions with saved models.

4. **Streamlit App:**  
   - Launch the UI:
     ```
     streamlit run app.py
     ```
   - Deploy the app via Streamlit sharing using this GitHub repo.




---

## 📁 Project Structure

```
Churn_analysis/
│
├── experiments.ipynb
├── prediction.ipynb
├── requirements.txt
├── Simple RNN/
│   ├── implementation.ipynb
│   └── embedding.ipynb
├── app.py
├── README.md
└── assets/
    ├── banner.png
    ├── tensorboard.png
    └── app_screenshot.png
```

---

## 💡 How It Works

- **Data Preparation:** Clean and preprocess the dataset.
- **Feature Engineering:** Transform features and save using Pickle.
- **Model Training:** Train ANN and RNN models, log metrics with TensorBoard.
- **Prediction:** Load serialized models for new predictions.
- **Deployment:** Streamlit app for interactive predictions.


