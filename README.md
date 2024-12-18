# Data-Science-and-Analytics-Using-Azure-Cloud-Computing-Technologies

The project integrates Azure services and machine learning models to address business challenges such as Customer Lifetime Value (CLV) prediction and churn analysis. 


## Table of Contents
1. [Project Description](#project-description)
2. [Technologies Used](#technologies-used)
3. [Features](#features)
4. [Setup and Installation](#setup-and-installation)
5. [How to Use](#how-to-use)
6. [ML Models](#ml-models)
7. [Tasks](#tasks)

---

## Project Description
This project demonstrates the use of **Azure Cloud Computing Technologies** for developing a data-driven web application. Key components include:
- **Interactive Web Pages**: For data visualization and ML applications.
- **Machine Learning Models**: Designed for predicting customer behavior, such as CLV and churn.
- **Azure Integration**: Leveraging Azure services for deployment, data management, and scaling.

---

## Technologies Used
- **Azure Services**:
  - Azure Storage (Datastore)
  - Azure App Services (Web App Hosting)
- **Machine Learning Frameworks**:
  - Scikit-learn
  - Pandas
- **Web Development**:
  - Flask (Backend Framework)
  - SQLite3 (Database)
- **Visualization**:
  - Dash or Matplotlib (for interactive dashboards)

---

## Features
- **Write-Up on ML Models**: Comprehensive insights into Linear Regression, Random Forest, and Gradient Boosting.
- **Web Server Setup**: Secure web server deployment with user authentication (default credentials: username: `abhay`, password: `Abhay`).
- **Datastore and Data Loading**: Seamless integration with Azure for managing datasets.
- **Interactive Dashboard**: Real-time visualization of business insights, such as CLV and churn metrics.
- **Data Loading Web App**: A simple web interface for uploading and processing data.
- **Churn Prediction**: Uses ML models to identify customers at risk of leaving.

---

## Setup and Installation
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-repo-name.git
    ```
2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Configure Azure**:
   - Create an Azure Storage Account and configure the connection in the `config.json` file.
   - Deploy the web server using Azure App Service.
4. **Run the Application**:
    ```bash
    python app.py
    ```

---

## How to Use
1. **Log In or Register**: Use the default credentials (`username: abhay, password: Abhay`) or create a new account.
2. **Load Data**:
   - Navigate to the "Data Loading" page.
   - Upload datasets for ML models and dashboards.
3. **Interact with Dashboards**:
   - Explore visualizations for Customer Lifetime Value (CLV).
   - Analyze churn predictions.
4. **Run ML Models**:
   - Use the web interface to select and execute machine learning models.

---

## ML Models
### Linear Regression
- **Description**: Predicts continuous target variables by identifying linear relationships in the data.
- **Limitations**: Struggles with complex or nonlinear patterns.

### Random Forest
- **Description**: An ensemble method combining multiple decision trees for accurate predictions.
- **Advantages**: Robust against noise, handles high-dimensional data, and computes feature importance.

### Gradient Boosting
- **Description**: Iteratively improves predictions by minimizing the error of the previous models.
- **Use Case**: Effective for non-linear relationships but requires careful tuning.

---

## Tasks
1. **ML Model Write-Up**:
   - Detailed analysis of Linear Regression, Random Forest, and Gradient Boosting.
   - Justification for using Random Forest for CLV prediction.

2. **Web Server Setup**:
   - Configured using Flask and hosted on Azure App Services.
   - Includes user authentication (default credentials: username: `abhay`, password: `Abhay`).

3. **Datastore and Data Loading**:
   - Integrated Azure Storage for secure and efficient data management.

4. **Interactive Web Page**:
   - Developed using Flask, with user-friendly navigation for loading and analyzing data.

5. **Data Loading Web App**:
   - Provides a simple interface for uploading datasets.

6. **Dashboard Integration**:
   - Real-time visualizations for key business metrics, such as CLV and churn.

7. **ML Model Application**:
   - Implemented machine learning models to predict CLV and churn.

8. **Churn Prediction**:
   - Identifies customers at risk of leaving using Random Forest.

---

