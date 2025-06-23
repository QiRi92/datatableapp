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

## 📸 Screenshots

### 📍 Homepage with Datatable  
<img width="913" alt="image" src="https://github.com/user-attachments/assets/1e0504e2-7ea9-4428-9f0d-4e916f42611f" />

### 📍 Graph View with Modal  
<img width="923" alt="image" src="https://github.com/user-attachments/assets/3c5a1744-5193-47c7-891b-95f9d808f50a" />

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

💼 GitHub: [QiRi92](https://github.com/QiRi92)

⭐️ If you like this project, give it a star and share it with others!
