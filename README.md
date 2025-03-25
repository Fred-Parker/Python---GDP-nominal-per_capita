# Python GDP (nominal) per Capita
A exploration of how **Python can be used to visualise / analyse datasets**. This project focuses on **examining relationships between different GDP estimates** provided by the UN, World Bank, and IMF for various countries and territories worldwide. By comparing these estimates, it aims to **identify patterns, discrepancies, and correlations** that can offer insights into **global economic assessments and their methodologies**.

<ul>
  <li><a href="#dataset description">Dataset Description</a></li>
  <li><a href="#Using Python Libraries to Explore & Visualise Data">Using Python Libraries to Explore & Visualise Data</a></li>
  <li><a href="#methodology / approach">Methodology / Approach</a></li>
  <li><a href="#visualisations">Visualisations</a></li>
  <li><a href="#key findings">Key Findings</a></li>
  <li><a href="#conclusions & insights">Conclusions & Insights</a></li>
  <li><a href="#challenges & limitations">Challenges & Limitations</a></li>
</ul>

<hr>
<h2 id="dataset description">Dataset Description</h2>
<li>The dataset contains 224 records, detailing GDP estimates from the UN, World Bank, and IMF, alongside the years these figures were recorded. This structure allows for meaningful comparisons and trend analysis across global economic data.</li>
<li>Data Source: Kaggle's dataset - https://www.kaggle.com/datasets/rajkumarpandey02/gdp-in-usd-per-capita-income-by-country/data </li>

<hr>
<h2 id="Using Python Libraries to Explore & Visualise Data">Using Python Libraries to Explore & Visualise Data</h2>

Pandas (Visualised using VSCode)
------
<li>Import the dataset into a pandas DataFrame for analysis.</li>
<li>Clean and pre-process the data (e.g., handle missing values, rename columns, or filter by year or country)</li>

![image](https://github.com/user-attachments/assets/ae8b853c-b1cf-44d1-a86f-3d93c67c14f7)

<li>Descriptive Analysis: Summarise the dataset using pandas to understand the range, mean, or variance of GDP estimates across the organisations.</li>

![image](https://github.com/user-attachments/assets/a0f0dc9a-7cf9-40b0-993c-5ed13071e885)

MatPlotLib - Visualising Data (Visualised using VSCode)
------
<li>Use line plots or bar plots to observe trends over time or compare GDP estimates by country.</li>

![image](https://github.com/user-attachments/assets/50e95137-ee2f-49b7-a5c7-a7de239b50dc)

Seaborn - Correlation Analysis (Visualised using VSCode)
------
<li>Use scatter plots and correlation heatmaps to investigate relationships between GDP estimates.</li>

![image](https://github.com/user-attachments/assets/82cd5db8-832a-481f-9ff7-69f3cd472ef9)

<hr>
<h2 id="methodology / approach">Methodology / Approach</h2>

<li>Data Cleaning: Managed missing values using averages and excluded outliers.</li>
<li>Exploratory Data Analysis: Computed average estimates and visualised positive or negative correlations between them.</li>
<li>Analysis: Assessed continent representation by counting country records. Calculated average IMF estimates per continent and analysed World Bank estimates by year and continent.</li>
<li>Visualisation: Created a correlation matrix and visualisations for the analysis insights above.</li>

<hr>
<h2 id="visualisations">Visualisations</h2>

**Correlation Matrix between estimates:**

![image](https://github.com/user-attachments/assets/b63141f0-32e1-4928-97d6-5479ca2f0ae0)

**Continents by IMF Estimate**

![image](https://github.com/user-attachments/assets/f5f17f0e-4a05-4cf4-8482-6f7c69068642)

**World Bank Estimates by Year & Continent**

![image](https://github.com/user-attachments/assets/1d756811-0852-47d1-9e74-47a7eea52442)

<hr>
<h2 id="key findings">Key Findings</h2>

<li>World Bank and UN GDP estimates demonstrate a strong positive correlation, while IMF estimates show weaker but still positive links with both the World Bank and UN.</li>
<li>Most continents are represented by roughly 50 country records, except Oceania, which includes only 20. Europe not only holds the highest GDP estimates but also boasts the most consistent record-keeping, unlike other continents with notable data gaps.</li>

<hr>
<h2 id="conclusions & insights">Conclusions & Insights</h2>

<li>The analysis requires organising records by year to avoid comparing GDP estimates from different timeframes.</li>
<li>Improving data accuracy requires addressing issues like significant missing data and incomplete year recordings within rows. Streamlining these aspects will enhance reliability and prevent misinterpretations.</li>
<li>Additionally, aligning data collection methodologies across organizations (UN, World Bank, IMF) could reduce discrepancies and allow for more consistent comparisons, providing deeper insights into global economic trends.</li>

<hr>
<h2 id="challenges & limitations">Challenges & Limitations</h2>

<li>11% of the dataset contained missing values—a significant proportion that likely affected the analysis's accuracy. While average estimates were used as replacements, this approach may have introduced bias or diluted genuine patterns in the data.</li>
<li>Addressing the root causes of these missing values and considering advanced imputation techniques could enhance the dataset’s reliability and the overall robustness of future analyses.</li>
