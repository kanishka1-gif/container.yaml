# 📌 YAML Data Processing in Python

This project showcases how to handle YAML files in Python, specifically for processing student data. It enables loading student details, displaying all records, and filtering students based on GPA.

---

## 📁 Project Structure

```
.
├── README.md
├── requirements.txt
├── students.yaml
└── app.py
```

---

## 🛠️ Components

### 📄 students.yaml
Contains student records in YAML format. Each entry includes:
- **name**
- **age**
- **major**
- **gpa**

Example:
```yaml
students:
  - name: Alice
    age: 21
    major: Computer Science
    gpa: 3.8
```

### 🖥️ app.py
The main script responsible for processing YAML data. It includes:

- `load_data(file_path)`: Loads and parses the YAML file.
- `display_students(students)`: Displays all student records.
- `filter_students_by_gpa(students, min_gpa)`: Filters students based on a given GPA threshold.
- `main()`: Manages the program execution.

### 📜 requirements.txt
Specifies project dependencies:
```txt
pyyaml==6.0.1
```

---

## 🚀 Setup & Installation

1. Clone or download this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage

1. Run the script:
   ```bash
   python app.py
   ```

2. The program will:
   - Display all students and their details.
   - Prompt you to enter a minimum GPA value.
   - Show students who meet or exceed the specified GPA.

---

## 🖥️ Example Output

<div align="center">
  <img src="/images/Screenshot 2025-04-01 154111.png" alt="Example Output">
</div>

---

## ✨ Features

✅ YAML file parsing using PyYAML  
✅ Simple student data management  
✅ GPA-based filtering  
✅ Well-structured & readable code  
✅ Error handling for file operations  

---

## 🛠️ Technical Details

- Uses `yaml.safe_load()` for secure YAML parsing.
- Student data is stored as a list of dictionaries.
- GPA filtering is implemented with list comprehension.
- Supports floating-point GPA values.

---

## 📌 Dependencies

- Python 3.x
- PyYAML 6.0.1

---

## ⚠️ Notes

🔹 Ensure `app.py` and `students.yaml` are in the same directory.  
🔹 Input YAML file must have valid syntax.  
🔹 GPA values should be numeric (floating-point).  

---

🚀 **Happy Coding!** 🎯
