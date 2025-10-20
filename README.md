# Student Result Analysis -Project

## What is included
- `Academic_Result_Dashboard_Dataset.xlsx` - dataset
- `Students_Dashboard.pbit` - Power BI template
- `Student_Result_Analysis.ipynb` - Jupyter notebook (open/run in Jupyter)
- `.ipynb_checkpoints/` -contains a notebook checkpoint copy
- `README.md` - this file

## Goal
Run the notebook to load and analyze the dataset, then automatically (or manually) open the Power BI template to view the dashboard.

---

## Steps to run (Windows recommended for Power BI Desktop)

1. Place the `Student_Result_Analysis` folder somewhere convenient (e.g., `Documents` or `Desktop`).

2. Open **Anaconda Prompt** and navigate to the project folder:
   ```
   cd "C:\Users\<YourUser>\Documents\Student_Result_Analysis"
   ```

3. Create and activate a conda environment:

   conda create -n sra python=3.10 -y
   conda activate sra 


4. Install required Python packages:
   pip install pandas openpyxl

   (Or use `conda install -c anaconda pandas openpyxl -y`)
   or
   conda install pandas openpyxl notebook -y

5. Start Jupyter Notebook:

   jupyter notebook

6. Click on `Student_Result_Analysis.ipynb` and then choose `Kernel -> chaneg kernel ->select python sra -->restart and run all cells` (or run all cells manually).

7. open students_dashboard.pbit manually


