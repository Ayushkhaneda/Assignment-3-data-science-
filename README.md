# Assignment-3-data-science-
Data science assignment in BTech cse 4th semester 

# Global Terrorism EDA - Capstone Project

This is my EDA capstone project where i analyzed the Global Terrorism Database. The dataset has records of terrorist attacks from 1970 to 2017 and i tried to find useful patterns and insights from it.

---

## About the Dataset

The dataset is from the Global Terrorism Database (GTD). It has around 181,000 rows and each row represents one terrorist attack. It has information like which country the attack happened in, what type of attack it was, which group did it, how many people were killed or wounded and what weapons were used.


---

## What i did in this project

First i loaded the dataset and explored it to understand what columns are there and what kind of data it has. Then i cleaned the data by handling missing values and checking for outliers. After that i made different charts to find patterns and insights.

### Data Cleaning
- Filled missing values in killed and wounded columns with 0
- Filled missing city names with Unknown
- Dropped rows where attack type, region or country was missing
- Used IQR method to check outliers but kept them because they are real events

### New columns i created
- Total Casualties = Killed + Wounded
- Decade column to group attacks by decade

---

## Charts i made

I made 15 different charts to understand the data better

1. Attacks per year - to see how terrorism changed over time
2. Top 10 countries with most attacks
3. Types of attacks and their percentage
4. Deaths by region
5. Heatmap of attacks by region and decade
6. Most active terrorist groups
7. Killed vs wounded over the years
8. Boxplot of casualties by attack type
9. Most used weapons
10. Which months have more attacks
11. Scatter plot of killed vs wounded
12. Success rate of attacks
13. Correlation between numerical columns
14. Attacks per decade
15. Pairplot of casualty columns

---

## What i found

- Terrorism increased a lot after 2011 and was highest around 2014
- Iraq Pakistan and Afghanistan have the most attacks
- Bombing is the most common type of attack around 50 percent
- Taliban and ISIS are the most active groups
- Middle East and South Asia have the most deaths
- The 2010s had more attacks than all previous decades combined

---

## Libraries i used

- Pandas - for loading and cleaning data
- NumPy - for calculations
- Matplotlib - for making charts
- Seaborn - for heatmaps and statistical charts

---

## How to run this project

1. Download the dataset from Kaggle (Global Terrorism Database)
2. Upload the csv file and the notebook to Google Drive
3. Open the notebook in Google Colab
4. Run all cells

---

## Project Structure

```
├── globalterroristEDAproject.ipynb
├── README.md
└── globalterrorismdb.csv
```

---

## Conclusion

After doing this analysis i found that terrorism has increased a lot especially in the Middle East and South Asia. Bombings are the most common attack method and groups like Taliban and ISIS are behind most of the attacks. This kind of analysis can help governments and security agencies make better decisions.

