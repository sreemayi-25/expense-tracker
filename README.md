# 💰 Django Expense Tracker

A Django-based web application that helps users track and manage their expenses efficiently. The app supports adding, updating, and deleting expenses, categorizing them, and visualizing data through weekly and monthly bar and pie charts. Styled with Bootstrap, the interface is user-friendly and responsive.

---

## 🚀 Features

- 🧾 **Add, Update, Delete Expenses**
- 📅 **Weekly and Monthly Expense Tables**
- 📊 **Bar and Pie Charts for Visualizing Spending**
- 🗂️ **Category-wise Expense Tracking**
- 👤 **User Authentication**
- 🧠 **Session-based Data Separation**
- 📱 **Bootstrap-Powered Responsive Design**

---

## 🖥️ Screenshots

*(Add screenshots of your UI, charts, and tables here to showcase the look and feel)*

---

## 🛠️ Tech Stack

- **Backend:** Django, SQLite/PostgreSQL
- **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript
- **Visualization:** Chart.js / Plotly (whichever you used)

---

## 🔧 Installation

1. **Clone the repository**
  ```bash
   git clone https://github.com/sreemayi-25/expense-tracker.git
   cd expense-tracker
```
2. **Create a virtual environment**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install the dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create a superuser (optional)**

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the server**

   ```bash
   python manage.py runserver
   ```

7. **Visit the app**
   Open your browser and go to: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🗃️ Project Structure

```
expense-tracker/
├── expenses/           # Core Django app handling all expense logic
├── templates/          # HTML templates
├── static/             # CSS, JS, Images
├── manage.py
├── db.sqlite3
└── requirements.txt
```

---

## 🧠 Usage Guide

1. **Register/Login** to your account.
2. **Add new expenses** under different categories (e.g., Food, Travel, Utilities).
3. **View weekly and monthly summaries** in tabular format.
4. **Visualize** your spending through bar and pie charts.
5. **Update or delete** any existing expense entries with ease.

---

## 📊 Categories Supported

* Food
* Travel
* Shopping
* Utilities
* Entertainment
* Others
  *(You can easily extend the categories in the admin panel)*

---

## 🔒 Authentication

* Each user's data is stored and retrieved individually.
* Only logged-in users can view or modify their own expenses.

---

## 📌 Future Enhancements

* Export data as CSV or PDF
* Set monthly budget goals
* Send email alerts for overspending

---

## 📝 License

This project is licensed under the MIT License.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📬 Contact

**Sreemayi Billa**
[LinkedIn](https://www.linkedin.com/in/sreemayi-billa)
Email: [sreemayi@example.com](mailto:sreemayi@example.com)

---
