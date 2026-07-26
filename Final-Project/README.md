# UNGTA: Global Terrorism Data Analysis (1970-2017)

📌 Business Context
The United Nations Global Terrorism Analysis (UNGTA) dataset is a comprehensive repository of over 180,000 terrorist incidents. This project aims to extract actionable insights to help stakeholders understand the evolving landscape of global security.

🛠️ Tech Stack
* **Environment:** Google Colab
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Data Source:** [Global Terrorism Database (GTD)](https://drive.google.com/file/d/1uu227cCTWvKIePOZiRYf6oxDzGeI8bpL/view?usp=sharing)

 📊 Key Visualizations
1. **Temporal Trends:** Analysis of attack frequency over decades.
2. **Regional Hot Zones:** Identification of high-intensity geographic areas.
3. **Tactical Success:** Success rates based on attack type (e.g., Bombing vs Assassination).
4. **Impact Assessment:** Distribution of fatalities using logarithmic scaling.
5. **Weapon Analysis:** Correlation between weapon choice and incident success.

 🤖 Machine Learning Models
We implemented and compared 5 algorithms to predict attack success:
* Logistic Regression
* Decision Tree
* Random Forest (Best Performing)
* K-Nearest Neighbors (KNN)
* Naive Bayes

💡 Stakeholder Utility
This analysis is useful for:
* **Security Agencies:** To prioritize border control and intelligence based on weapon trends.
* **Insurance Companies:** For calculating regional risk premiums.
* **NGOs:** To prepare medical resources in identified high-risk zones.

 📂 How to Run
1. Open the `.ipynb` file in Google Colab.
2. Mount your Google Drive.
3. Ensure the dataset is in your `MyDrive` folder.
