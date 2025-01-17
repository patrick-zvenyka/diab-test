
# 🏥 Diabetes Prediction System  

A **web-based Diabetes Prediction System** built with **Django** and **Bootstrap** to help users assess their risk of diabetes based on key medical parameters.  

## 🚀 Features  
✅ **User Input Form** – Collects patient details such as glucose level, BMI, blood pressure, etc.  
✅ **Machine Learning Model Integration** – Predicts the likelihood of diabetes based on input data  
✅ **Responsive UI** – Clean and user-friendly design using Bootstrap  
✅ **Real-time Results** – Instant prediction after form submission  
✅ **Authentication System** – Secure user login and registration  
✅ **Data Visualization** – Graphs and charts for better insights  
✅ **Admin Dashboard** – Manage users and view prediction statistics  

## 🛠️ Tech Stack  
- **Backend:** Django, Python  
- **Frontend:** HTML, CSS, Bootstrap  
- **Database:** SQLite/MySQL/PostgreSQL  
- **ML Model:** Scikit-learn (Logistic Regression/Decision Tree/etc.)  
- **Deployment:** Heroku/AWS/DigitalOcean (Optional)  

## 🎯 How to Run Locally  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/patrick-zvenyka/diab-test.git
   cd diab-test
   ```

2. **Create and activate a virtual environment**  
   ```bash
   python -m venv env
   source env/bin/activate  # For Mac/Linux
   env\Scripts\activate  # For Windows
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run database migrations**  
   ```bash
   python manage.py migrate
   ```

5. **Start the development server**  
   ```bash
   python manage.py runserver
   ```

6. **Access the application**  
   Open your browser and go to:  
   ```
   http://127.0.0.1:8000/
   ```

## 📌 Future Improvements  
- Integration with **electronic health records (EHR)**  
- More **advanced AI models** for higher accuracy  
- Mobile app version  



