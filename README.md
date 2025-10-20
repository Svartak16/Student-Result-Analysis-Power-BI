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

OUTPUTS:
![image alt](https://github.com/Svartak16/Student-Result-Analysis-Power-BI/blob/2a2e47013a81579fce1c692bae524963f6e40dbc/activate%20conda.png)
![image alt](https://github.com/Svartak16/Student-Result-Analysis-Power-BI/blob/c1835d5b64f530cb9de994be7a318485fbe4d6e2/home%20page%20of%20jupyter%20notebook.png)
![image alt](https://github.com/Svartak16/Student-Result-Analysis-Power-BI/blob/450487a163ed60b2ed35af890d2716d66074f337/run%20jupyter%20source%20file.png)
![Image](https://github.com/user-attachments/assets/170e4045-8c00-4559-8167-d92dfa2ff14a)
