# Student Performance Prediction System (AI/ML)

Beginner-friendly internship mini-project aligned to the assignment workflow.

## Project objective
Train a regression model to estimate a student's final score from study hours, attendance, previous score, and assignment completion.

## Files
- `dataset/student_data.csv`: practice dataset with 300 synthetic rows.
- `notebooks/student_performance.ipynb`: notebook with data loading, cleaning, EDA, feature selection, train/test split, model training, evaluation, and prediction.
- `requirements.txt`: Python packages needed locally.
- `report/`: place your final project report here.
- `visualizations/`: place exported charts here.

## Easiest run option (Google Colab; no local Python setup required)
1. Open https://colab.research.google.com/ and create a New Notebook.
2. Upload `dataset/student_data.csv` using the Files panel.
3. Upload/open the notebook `notebooks/student_performance.ipynb` (or copy its cells into a Colab notebook).
4. In Colab, change the dataset load cell to `df = pd.read_csv('/content/student_data.csv')`.
5. Run cells from top to bottom. Colab generally already has the listed packages; if imports fail, run `!pip install -r requirements.txt` after uploading requirements.

## Run locally (once Python is installed)
From the project root in VS Code terminal:
```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
jupyter notebook
```
Then open `notebooks/student_performance.ipynb`. The notebook reads the CSV with a relative path, so start Jupyter from the project root.

## Important
The CSV data is synthetic and made only for practice. Do not claim it is real student data. Understand and explain each step; customize the analysis and report before submission, as the internship asks interns not to copy a complete project blindly.
