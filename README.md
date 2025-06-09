
# Climate Change Survey Data Analysis with Machine Learning

---

## 1. STEP-BY-STEP INSTRUCTIONS

To run the analysis from start to finish, follow these steps:

1. **Download and extract** the ZIP archive containing this project.  
2. Ensure you have **Python 3.8 or above** installed (preferably via Anaconda or a virtual environment).  
3. Open the provided Google Colab notebook (link inside `Colab_Link.txt`) **OR** run `main_analysis.ipynb` locally.  
4. *(Optional)* Install required Python libraries using `pip install -r requirements.txt`.  
5. Execute the notebook cells in order. The notebook handles:
   - Data loading and cleaning  
   - Exploratory data analysis (EDA)  
   - Correlation analysis  
   - Regression modeling (linear & logistic)  
   - Model evaluation  
   - Visualization of results

---

## 2. DEPENDENCIES

This project depends on the following Python libraries:

- pandas==2.2.2  
- numpy==1.26.4  
- matplotlib==3.8.4  
- seaborn==0.13.2  
- scikit-learn==1.4.2  

These are listed in the file: `requirements.txt`

### ▶ LOCAL INSTALLATION (recommended via virtual environment):

**Step 1**: Create and activate a virtual environment  
- *Windows*:
```bash
python -m venv venv  
venv\Scripts\activate
```
- *macOS/Linux*:
```bash
python3 -m venv venv  
source venv/bin/activate
```

**Step 2**: Install dependencies
```bash
pip install -r requirements.txt
```

### ▶ GOOGLE COLAB:

These libraries are usually pre-installed.  
If needed, run this in a Colab cell:
```python
!pip install pandas==2.2.2 numpy==1.26.4 matplotlib==3.8.4 seaborn==0.13.2 scikit-learn==1.4.2
```

---

## 3. EXPECTED OUTPUTS

Running the analysis will generate:

- Summary statistics and correlation matrices  
- Linear regression results (e.g., prediction of climate concern score)  
- Logistic regression output (e.g., predicting support for climate policy)  
- Visualizations (e.g., heatmaps, scatter plots, regression lines)  
- Model evaluation metrics such as R², accuracy, precision/recall  
- Interpretation and commentary on the findings (in notebook markdown cells)

---

## 4. DOCUMENTATION OF FILES

Here’s what each file does:

- `CLIM8S_DS2025_Report.docx` – Report with results and workflow explanation  
- `README.md` – This file: setup, instructions, and documentation  
- `survey_178.csv` – The dataset used for analysis  
- `main_analysis.ipynb` – The complete Colab/Jupyter notebook with code and discussion  
- `requirements.txt` – List of required libraries and versions  
- `Colab_Link.txt` – Shareable Google Colab link  
- `figures/` – Folder with generated plots  
- `models/` – Folder with saved ML models used

---

## 👥 Project Contributors

**Dana Hamdan**  
**Ali Mehri**  
**Sherif Khairy**  
**Mohamed Shedid**  
**Anthony Mansour**  
**Antonio Petrarulo**  
**Mohannad El Sahmarani**  
**Amir Bayat**

Students at **Politecnico di Torino**  
MSc in *Georesources and Geoenergy Engineering*  
MSc in *Chemical and Sustainable Processes Engineering*

**Course**: Data Science & Machine Learning for Engineering Applications  
**Instructor**: Prof. Daniele Quercia

**Date**: June 2025
