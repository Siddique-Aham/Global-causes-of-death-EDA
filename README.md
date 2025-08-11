
#  Exploratory Data Analysis on Global Causes of Death

This project performs a comprehensive Exploratory Data Analysis (EDA) on a global dataset of causes of death, sourced from Kaggle. The goal is to identify the most frequent causes of death, visualize the trends, and extract meaningful insights that can support further public health analysis and decision-making.

---

## 📦 Dataset

- **Source**: Kaggle
- **Search Term Used**: "causes of death"
- **Format**: CSV
- **Contents**: 
  - Country/Territory
  - Year
  - Code (ISO alpha code)
  - Various causes of death (columns containing death counts)

---

## 🧰 Technologies & Libraries Used

- Python 3.x
- [Kaggle API](https://github.com/Kaggle/kaggle-api)
- pandas
- numpy
- seaborn
- matplotlib
- zipfile
- os

---

## 🗂️ Project Structure

### 1. **Data Loading**
- Used the Kaggle API to search for datasets containing information about causes of death.
- Downloaded and extracted the dataset programmatically.
- Loaded the dataset into a Pandas DataFrame.

### 2. **Data Exploration**
- Viewed the first few rows of the dataset.
- Checked column types, number of unique values, and null counts.
- Generated descriptive statistics for numerical data.

### 3. **Data Cleaning**
- Verified no missing values existed.
- Ensured columns had appropriate data types.
- Removed non-relevant columns (`Country/Territory`, `Year`, `Code`) for analysis.

### 4. **Analysis**
- Aggregated the total number of deaths for each cause across all countries and years.
- Sorted and identified the top 10 causes of death globally.

### 5. **Visualization**
- Created a bar chart showing the 10 most frequent causes of death using `seaborn` and `matplotlib`.

---

## 📊 Key Findings

- The dataset contains **6,120 rows** and **34 columns**, with **no missing values**.
- The **top 10 causes of death globally** (based on total deaths across all entries) are:

  1. Cardiovascular Diseases  
  2. Neoplasms  
  3. Chronic Respiratory Diseases  
  4. Lower Respiratory Infections  
  5. Neonatal Disorders  
  6. Diarrheal Diseases  
  7. Digestive Diseases  
  8. Tuberculosis  
  9. Cirrhosis and Other Chronic Liver Diseases  
  10. HIV/AIDS

- Cardiovascular diseases are by far the most significant contributor to global mortality.

---

## 📈 Visual Output

A bar chart visualizes the top 10 causes of death, clearly showing the magnitude of each cause.

![Top Causes of Death Chart](your-chart-image-path-if-exported)

---

## 🔮 Future Work

- **Trend Analysis**: Investigate how causes of death change over time.
- **Geographic Comparison**: Compare death causes by country or region.
- **Normalization**: Incorporate population data to compute death rates per capita.
- **Predictive Modeling**: Use machine learning to predict future mortality trends.

---

## ▶️ How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Siddique-Aham/causes-of-death-eda.git
   cd causes-of-death-eda
````

2. **Install Required Libraries**

   ```bash
   pip install -r requirements.txt
   ```

3. **Setup Kaggle API Credentials**

   * Go to your Kaggle account → Account → Create new API token.
   * Place the `kaggle.json` file in either:

     * `~/.kaggle/` or
     * `~/.config/kaggle/`
   * Authenticate using the Kaggle API.

4. **Run the Notebook**

   * Open `Untitled5.ipynb` in Jupyter Notebook or Google Colab.

---

## 📜 License

This project is for educational purposes only. The dataset used may have its own license — please consult the Kaggle page of the dataset for more information.

---

## 👤 Author

* **Your Name**
* GitHub: [@Siddique-Aham (https://github.com/Siddique-Aham
