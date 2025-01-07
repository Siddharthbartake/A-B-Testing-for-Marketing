# A/B Testing for Marketing Campaigns

This project is designed to analyze the performance of two marketing campaigns, Control and Test, using A/B testing methodologies. By comparing key metrics such as advertising spend, impressions, website clicks, and purchases, the analysis identifies the more effective campaign.

---

## 📂 Datasets

- **Control Group:** Represents data collected from the control campaign.
- **Test Group:** Represents data collected from the test campaign.

### Columns in Both Datasets:
- `Campaign Name`
- `Date`
- `Spend [USD]`
- `# of Impressions`
- `Reach`
- `# of Website Clicks`
- `# of Searches`
- `# of View Content`
- `# of Add to Cart`
- `# of Purchase`

---

## 🛠️ Analysis Workflow

### 1. **Data Cleaning**
   - Processed date columns and resolved missing values to ensure data integrity.

### 2. **Descriptive Statistics**
   - Generated summary statistics to provide insights into campaign performance.

### 3. **Exploratory Data Analysis (EDA)**
   - Visualized key metrics such as spend, website clicks, and purchases to identify trends and differences between campaigns.
   - **Example Visualization:**
     Below is the spend distribution plot, highlighting the advertising spend variations between the control and test campaigns.

     <img width="915" alt="Spend Distribution Plot" src="https://github.com/user-attachments/assets/d5839062-dead-431f-98dc-374ed630c450">

### 4. **A/B Testing**
   - Performed statistical hypothesis testing using T-tests to compare campaign performance metrics.

### 5. **ROI and Conversion Rates**
   - Calculated key performance indicators such as conversion rates and return on investment (ROI) to evaluate campaign effectiveness.

### 6. **Final Recommendations**
   - Delivered actionable insights by identifying the more successful campaign based on data analysis and statistical results.

---

## ⚙️ Requirements

To run the analysis, you need the following Python libraries:

- `pandas`
- `numpy`
- `scipy`
- `matplotlib`
- `seaborn`

---

## 💡 How to Use

1. Clone this repository to your local machine.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Run the script to perform data cleaning, analysis, and A/B testing.
4. Review the visualizations and recommendations for campaign decisions.

---


