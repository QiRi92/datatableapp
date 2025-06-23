# 📊 DatatableApp

DatatableApp is a Django-based web application designed to dynamically display tabular data with interactive search, pagination, and sorting capabilities using DataTables.js. This project integrates modern front-end features with Django's robust backend, enabling users to explore large datasets efficiently.

---

## 🚀 Features

- 🔍 **Live search & filtering**
- ⏳ **Pagination**
- 📁 **Dynamic data fetching using AJAX**
- 📉 **Graph generation based on selected row**
- 📦 **SQLite integration with Django ORM**
- ✅ **Modal display for row-based detail**
- 📊 **Chart.js integration for visual data exploration**

---

## 🛠️ Tech Stack

| Layer        | Tech Used                     |
|--------------|-------------------------------|
| Frontend     | HTML5, Bootstrap, DataTables.js, Chart.js |
| Backend      | Python 3, Django Framework     |
| Database     | SQLite (default Django DB)     |

---


---

## 📸 Screenshots

### 📍 Homepage with Datatable  
![](https://titoluthi.pythonanywhere.com/static/screenshot_home.png)

### 📍 Graph View with Modal  
![](https://titoluthi.pythonanywhere.com/static/screenshot_graph.png)

---

## 🔧 Setup Instructions

### 1. 📥 Clone the repository

```bash
git clone https://github.com/QiRi92/datatableapp.git
cd datatableapp
```

### 2. 🐍 Create virtual environment & activate

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. 📦 Install dependencies

```bash
pip install -r requirements.txt
```

### 4. 🔌 Run migrations

```bash
python manage.py migrate
```

### 5. 🚀 Run the development server

```bash
python manage.py runserver
```

Then visit: http://127.0.0.1:8000

## 📈 Future Enhancements

- ✅ Authentication (Login/Logout, Admin View)

- 📤 CSV Upload via frontend

- 📦 PostgreSQL production-ready support

- 🛡️ Unit & integration testing (Pytest/Django Test Framework)

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, submit issues, or make pull requests.

## 🙋‍♂️ Author

💼 GitHub: @QiRi92

⭐️ If you like this project, give it a star and share it with others!
