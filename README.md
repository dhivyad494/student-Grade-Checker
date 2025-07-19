# student Grade Checker
A simple Flask web app to calculate student grades based on marks
# 🎓 Student Grade Checker (Flask Project)
  This is a simple web application built using **Python Flask** that allows users to input a student's name and mark, then calculates and displays the corresponding **Grade** based on the entered score.

Features
💡 User-friendly web interface  
📝 Form to input name and mark  
📊 Grade calculation based on marks  
🎯 Displays grade: A+, A, B, C, or Fail  
🔄 Built using Flask, Python, and HTML 

## 🛠️ Technologies Used

Python  
Flask Framework  
HTML (Jinja2 templating)  
VS Code  

How Grades are Calculated

| Marks Range | Grade |
|-------------|--------|
| 90+         | A+     |
| 75-89       | A      |
| 60-74       | B      |
| 50-59       | C      |
| Below 50    | Fail   |

How to Run Locally

# Step 1: Clone the repo
git clone https://github.com/your-username/student-grade-checker.git

# Step 2: Move to project directory
cd student-grade-checker

# Step 3: (Optional) Create virtual environment
python -m venv venv
venv\Scripts\activate     

# Step 4: Install Flask
pip install flask

# Step 5: Run the app
python app.py
Then open your browser and go to 👉 `http://127.0.0.1:5000/`




