# 🌸 Iris Flower Prediction Web App

**Live Demo**: [https://nvrpghuman-1.onrender.com](https://nvrpghuman-1.onrender.com)

This project is a simple machine learning web app that predicts the species of an Iris flower using user-provided input for sepal and petal measurements.

---

## 🛠️ Prerequisites

Before you begin, make sure you have the following installed:

1. **Python** ≥ 3.11
   👉 Download: [https://www.python.org/downloads/](https://www.python.org/downloads/)

2. **Visual Studio Code (VS Code)**
   👉 Download: [https://code.visualstudio.com/](https://code.visualstudio.com/)
   While installing, make sure to:

   * Check **"Add to PATH"**
   * Check **"Add 'Open with Code' to Windows Explorer"**

---

## 🚀 Getting Started

### Step 1: Open VS Code and Create/Open Project Folder

Open the folder where you want to create the project.

---

### Step 2: Install Required Python Packages

Open the terminal in VS Code and run the following command:

```bash
pip install flask scikit-learn pandas numpy
```

---

### Step 3: Create `app.py`

Inside your project folder, create a file named `app.py`. Add your Flask and ML code here.

---

### Step 4: Run the App Locally

In the terminal, run:

```bash
python app.py
```

This should start a local development server (usually at `http://127.0.0.1:5000`).

---

### Step 5: Push Project to GitHub

1. Initialize a git repository:

   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. Push to GitHub:

   ```bash
   git remote add origin https://github.com/your-username/your-repo-name.git
   git push -u origin main
   ```

---

### Step 6: Deploy on [Render](https://render.com)

1. Go to [https://render.com](https://render.com) and log in.
2. Click on **New Web Service**.
3. Connect your GitHub repository.
4. Fill out the deployment settings:

   * **Build Command**: `pip install -r requirements.txt`
   * **Start Command**: `python app.py`
5. Click **Deploy**.

---

## 📦 Useful Links

* ✅ Live Project: [nvrpghuman-1.onrender.com](https://nvrpghuman-1.onrender.com)
* 📂 GitHub Repo: [https://github.com/panesar880-svg/nvrpghuman](https://github.com/panesar880-svg/nvrpghuman)
* 🐍 Python: [https://python.org](https://python.org)
* 🧠 Scikit-learn Docs: [https://scikit-learn.org](https://scikit-learn.org)

---

## ✅ Summary

| Step | Task                    |
| ---- | ----------------------- |
| 1    | Install Python          |
| 2    | Install VS Code         |
| 3    | Open folder in VS Code  |
| 4    | Install Python packages |
| 5    | Create and run `app.py` |
| 6    | Push to GitHub          |
| 7    | Deploy on Render        |

---

Or you can Deploy on Gunicorn production server
