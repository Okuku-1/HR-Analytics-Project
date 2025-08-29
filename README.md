# HR Analytics Project

This project explores an HR dataset of **311 employees** with **36 attributes**, covering demographics, compensation, performance, engagement, and absenteeism. The goal is to analyze workforce patterns, test hypotheses, and apply dimensionality reduction (PCA) and clustering techniques to uncover hidden insights.

---

## 📂 Contents
- `HR_Analytics_Report.pdf` → Final comprehensive report  
- `analysis.Rmd` → R Markdown file with full code and explanations  
- `HRDataset_v14.csv` → HR dataset 
    

---

## 📊 Key Analyses
1. **Descriptive Statistics & Visualizations**  
   - Employee age, salary, and departmental distributions  
   - Employment status and termination trends  
   - Salary distribution histograms  

2. **Comparative Analyses**  
   - Salary vs race, gender, marital status  
   - Engagement and satisfaction differences across departments  
   - Performance vs salary relationship  

3. **Absenteeism**  
   - Absences distribution  
   - Identification of outliers  
   - Boxplot analysis of absenteeism patterns  

4. **Principal Component Analysis (PCA)**  
   - Standardized numeric features for PCA  
   - PC1: Performance & engagement vs workload/lateness  
   - PC2: Departmental/managerial influence  
   - Scree plot and loading plots  

5. **Clustering**  
   - K-means on original data vs PCA-reduced data  
   - PCA-based clustering yielded cleaner, more interpretable groups  
   - Clusters align with engagement and performance dimensions  

---

## 🔑 Key Insights
- No significant gender or marital salary gap detected.  
- Engagement and satisfaction vary by department → targeted interventions needed.  
- Absenteeism outliers highlight potential issues (health, burnout, management).  
- PCA reduced dataset complexity, revealing two latent employee dimensions.  
- Clustering on PCA features improves segmentation for HR planning.  

---

## ✅ Recommendations
- Launch engagement initiatives in departments with lower satisfaction.  
- Investigate high absenteeism cases for underlying causes.  
- Use PCA features in predictive HR models (attrition, performance).  
- Adopt clustering results for employee segmentation in HR strategy.  

---
