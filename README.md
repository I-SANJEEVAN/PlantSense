```markdown
🌱 PlantSense 🌿

PlantSense is a machine learning-based application designed to identify medicinal plants through image classification, with a Flask-powered backend and a React-based frontend. This guide will walk you through setting up the environment and running the project.

---

🛠️ Requirements:

1. Python Setup
Ensure you have Python 3.8 installed. Else,Download it from the link below:

🔗 [Download Python 3.8](https://www.python.org/ftp/python/3.8.10/python-3.8.10-amd64.exe)

 2. Installing Dependencies
[a] Install pip : 
`pip` is the package installer for Python. If it's not installed, run the following commands in the terminal:

```bash
python -m ensurepip --upgrade
python -m pip install --upgrade pip
```

#### b. Install TensorFlow
TensorFlow is essential for running the plant identification model.
```bash
pip install tensorflow
```

#### c. Navigate to the Correct Python Directory
Before installing other packages, make sure you're in the correct directory:
```bash
cd C:\Users\sanje\AppData\Local\Programs\Python\Python312\Scripts\
```

#### d. Install Flask
Flask is the web framework used for the backend of the PlantSense project:
```bash
C:\Users\sanje\AppData\Local\Programs\Python\Python38\python.exe -m pip install Flask
```

#### e. Install Pillow (PIL)
Pillow, a Python Imaging Library fork, is necessary for image handling and processing:
```bash
C:\Users\sanje\AppData\Local\Programs\Python\Python38\python.exe -m pip install Pillow
```

#### f. Install Pandas
Pandas is a data analysis library that may be useful for additional data handling in the backend:
```bash
C:\Users\sanje\AppData\Local\Programs\Python\Python38\python.exe -m pip install pandas
```

## Running the Project

### 1. Frontend
To launch the frontend (React-based interface), navigate to the frontend directory of the project and run:
```bash
npm run dev
```

### 2. Backend
To start the backend server (Flask), navigate to the backend directory and run the following command:
```bash
python app.py
```

With both the frontend and backend running, you can access PlantSense through a browser and begin identifying medicinal plants.

## Additional Information
For troubleshooting installation issues or learning more about the tools used, refer to the respective documentation:
- [TensorFlow Documentation](https://www.tensorflow.org/install)
- [Flask Documentation](https://flask.palletsprojects.com/en/2.0.x/installation/)
- [Pillow Documentation](https://pillow.readthedocs.io/en/stable/installation.html)
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
```
