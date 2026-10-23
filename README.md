#  Laptop Price Predictor

##  Project Overview

**Laptop Price Predictor** is a Machine Learning web application that estimates laptop prices based on their specifications. Users can select features such as brand, laptop type, RAM, processor, storage, graphics card, operating system, and display configuration to obtain an estimated price.

The project demonstrates how Machine Learning can be used to build an interactive, user-friendly application for predicting laptop prices.

##  Technologies Used

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Web Application:** Streamlit
- **Model Serialization:** Pickle
- **Development Environment:** Jupyter Notebook / PyCharm

##  Input Features

The prediction model can use the following laptop specifications:

| Feature | Description |
|---|---|
| Company | Laptop brand |
| TypeName | Laptop category |
| RAM | Memory capacity |
| Weight | Laptop weight |
| Touchscreen | Touchscreen availability |
| IPS | IPS display availability |
| Screen Size | Display size |
| Resolution | Display resolution |
| CPU | Processor information |
| HDD | Hard disk capacity |
| SSD | SSD capacity |
| GPU | Graphics processor |
| OS | Operating system |

##  Project Workflow

1. Collect and load the laptop dataset.
2. Perform exploratory data analysis (EDA).
3. Clean and preprocess the data.
4. Apply feature engineering and encoding.
5. Train and evaluate Machine Learning models.
6. Save the trained model and required data objects.
7. Develop the prediction interface using Streamlit.
8. Display the estimated laptop price based on user inputs.

##  Future Improvements

- Add more laptop brands and configurations.
- Improve prediction accuracy through model evaluation and tuning.
- Add laptop price comparisons across different configurations.
- Deploy the application to a cloud hosting platform.
- Improve the interface with additional visualizations.
