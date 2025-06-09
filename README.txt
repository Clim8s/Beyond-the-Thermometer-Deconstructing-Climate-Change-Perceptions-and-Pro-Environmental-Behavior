````
README.txt  
Climate Change Survey Data Analysis with Machine Learning  
==================================================================

1. STEP-BY-STEP INSTRUCTIONS
-----------------------------
To run the analysis from start to finish, follow these steps:

1.1. Download and extract the ZIP archive containing this project.  
1.2. Ensure you have Python 3.8 or above installed (preferably via Anaconda or a virtual environment).  
1.3. Open the provided Google Colab notebook (link inside `Colab_Link.txt`) **OR** run `main_analysis.ipynb` locally.  
1.4. (Optional) Install required Python libraries using `pip install -r requirements.txt`.  
1.5. Execute the notebook cells in order. The notebook handles:
     - Data loading and cleaning
     - Exploratory data analysis (EDA)
     - Correlation analysis
     - Regression modeling (linear & logistic)
     - Model evaluation
     - Visualization of results

2. DEPENDENCIES
---------------
This project depends on the following Python libraries:

- pandas==2.2.2  
- numpy==1.26.4  
- matplotlib==3.8.4  
- seaborn==0.13.2  
- scikit-learn==1.4.2  

These are listed in the file: `requirements.txt`

▶ LOCAL INSTALLATION (recommended via virtual environment):

Step 1: Create and activate a virtual environment  
(Windows)
    python -m venv venv  
    venv\Scripts\activate  
(macOS/Linux)
    python3 -m venv venv  
    source venv/bin/activate  

Step 2: Install dependencies  
    pip install -r requirements.txt

▶ GOOGLE COLAB:

These libraries are usually pre-installed.  
If needed, you can run this in a Colab cell:

```python
!pip install pandas==2.2.2 numpy==1.26.4 matplotlib==3.8.4 seaborn==0.13.2 scikit-learn==1.4.2
````

3. EXPECTED OUTPUTS

---

Running the analysis will generate:

- Summary statistics and correlation matrices  
- Linear regression results (e.g., prediction of climate concern score)  
- Logistic regression output (e.g., predicting support for climate policy)  
- Visualizations (e.g., heatmaps, scatter plots, regression lines)  
- Model evaluation metrics such as RÂ², accuracy, precision/recall  
- Interpretation and commentary on the findings (in notebook markdown cells)
Running the notebook will generate:


4. DOCUMENTATION OF FILES

---

Here’s what each file does:

* `CLIM8S_DS2025_Report.docx`- This file includes the reports with results and workflow explanation.
* `README.txt` – This file; setup, instructions, and documentation.
* `survey_178.csv` – The dataset used for analysis.
* `main_analysis.ipynb` – The complete Colab/Jupyter notebook with code and discussion.
* `requirements.txt` – List of libraries and versions required to run the notebook.
* `Colab_Link.txt` – Contains a shareable Google Colab link.
* `figures/` (folder) – Stores generated plots.
* `models/` (folder) – Stores saved ML models used.


\==================================================================
Project by Clim8s Team, MSc in Georesources and Geoenergy + Msc in Chemical and Sustainable Engineering
\Politecnico di Torino, \Data Science and machine learning for engineering applications by Prof. Daniele Quercia
Date: 09/06/2025
====================



---