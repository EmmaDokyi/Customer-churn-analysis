# 📞 TelecomX Customer Churn Analysis & Prediction

**Project Date:** April 2024  
**Tools Used:** Power BI, Python (Pandas, Scikit-learn), Excel


## 🗂️ PROJECT BACKGROUND

TelecomX is a growing telecom provider aiming to boost its market share in a highly competitive and saturated industry. Since acquiring new customers is up to five times more expensive than retaining existing ones, the company sought to analyze churn behavior, identify high-risk customer segments, and develop a churn prediction system to support proactive retention strategies.


## 📌 EXECUTIVE SUMMARY

With a churn rate of **26.5%** over six years—peaking at **61% in the first month**—the analysis revealed that churn decreases with customer tenure, contract length, and bundled service usage. The company generated **$16.1 million** in revenue from **7,043 subscribers** over six years but lost an estimated **$500K** from first-year churn alone. A machine learning model was developed to predict potential churners with over **93% accuracy**.

The entire interactive PowerBI dashboard can be downloaded [here](https://github.com/EmmaDokyi/Customer-churn-analysis/raw/refs/heads/main/Dashboard-Customer-churn-analysis.pbix)

![Alt text](https://github.com/EmmaDokyi/images/blob/main/Customer%20Churn%20Summary.png?raw=true)


## 📊 KEY INSIGHTS

- 📉 **Churn declines with tenure**: 47% churn in the first year drops to 6.6% by the sixth year.
- 💰 **High-paying customers churn more**: Customers with higher monthly charges are more likely to leave, possibly due to dissatisfaction or better offers elsewhere.
- 📄 **Contract length matters**: Month-to-month contracts have a 43% churn rate versus much lower rates for 1–2 year contracts.
- 🧾 **Service bundling reduces churn**: Customers lacking online security, backup, or tech support had churn rates over 41%.
- 👥 **Demographic patterns**: Senior citizens, customers with no partners, or no dependents were more likely to churn.
- 💳 **Payment method trends**: Electronic check users had the highest churn (45%) vs. those using mailed checks, bank transfers, or credit cards.

---

## 🤖 MODEL BUILDING

Built two machine learning models using `scikit-learn`:

- **Decision Tree Classifier**  
  - Accuracy: 92%  
  - Precision: 94% (non-churners), 92% (churners)

- **Random Forest Classifier** *(selected model)*  
  - Accuracy: 93%  
  - Precision: 96% (non-churners), 92% (churners)

✅ The **Random Forest model** was selected for deployment due to its superior performance and precision in predicting customer retention.

---

## 💼 OUTCOME

This analysis provided TelecomX with a data-driven understanding of its churn dynamics and a predictive model to proactively identify high-risk customers. Recommendations include targeting short-tenure and high-churn segments with tailored retention offers, bundling value-added services, and refining pricing strategies to reduce churn.

---

## 👨‍💻 Author

**Emmanuel Owusu Dokyi**  
📧 emmadokyi@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/)

---
