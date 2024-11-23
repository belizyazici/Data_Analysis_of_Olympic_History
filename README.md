# Data Analysis of Olympic History Dataset
This project involves a comprehensive exploration and analysis of the <b> 120 Years of Olympic History: Athletes and Results </b> dataset. 

## Table of Contents
<ol>
        <li><a href="#project-description">Project Description</a></li>
        <li><a href="#dataset-overview">Dataset Overview</a></li>
        <li><a href="#key-steps">Key Steps</a>
            <ul>
                <li><a href="#data-cleaning-and-preprocessing">Data Cleaning and Preprocessing</a></li>
                <li><a href="#exploratory-data-analysis">Exploratory Data Analysis (EDA)</a></li>
                <li><a href="#statistical-insights">Statistical Insights</a></li>
                <li><a href="#feature-selection">Feature Selection</a></li>
            </ul>
        </li>
        <li><a href="#visualizations">Visualizations</a></li>
        <li><a href="#key-insights">Key Insights</a></li>
    </ol>

<h2 id="project-description"><b>Project Description</b></h2>
The project is centered on analyzing historical data from the Olympic Games. It provides insights into trends, relationships between variables, and the distribution of athletes' characteristics such as age, height, weight, and medal achievements.

<h2 id="dataset-overview"><b>Dataset Overview</b></h2>
The dataset contains:

<ul>
        <li><b><code>athlete_events.csv</code></b>: Records of athletes' performances.</li>
        <li><b>Columns include</b>: <code>Name</code>, <code>Sex</code>, <code>Age</code>, <code>Height</code>, <code>Weight</code>, <code>Team</code>, <code>NOC</code>, <code>Medal</code>, and more.</li>
</ul>

<h2 id="key-steps"><b>Key Steps</b></h2>
 <h3 id="data-cleaning-and-preprocessing">1. Data Cleaning and Preprocessing</h3>
    <ul>
        <li>Handled missing values in <code>Height</code>, <code>Weight</code>, and <code>Medal</code> columns.</li>
        <li>Replaced missing <code>Age</code> values with the column mean.</li>
        <li>Verified data integrity through summary statistics and visual checks.</li>
    </ul>
<h3 id="exploratory-data-analysis">2. Exploratory Data Analysis (EDA)</h3>
    <ul>
        <li>Explored distributions of numerical variables (<code>Age</code>, <code>Height</code>, <code>Weight</code>).</li>
        <li>Visualized categorical data like <code>Sport</code> and <code>Medal</code>.</li>
        <li>Analyzed relationships, such as between <code>Age</code> and <code>Weight</code>.</li>
    </ul>
<h3 id="statistical-insights">3. Statistical Insights</h3>
    <ul>
        <li>Computed statistical measures (mean, median, mode, standard deviation) for numerical columns.</li>
        <li>Generated correlation matrices to identify relationships between variables.</li>
    </ul>
<h3 id="feature-selection">4. Feature Selection</h3>
    <ul>
        <li>Selected features based on correlation and importance for potential machine learning models.</li>
        <li>Performed feature engineering to create additional meaningful variables.</li>
    </ul>

<h2 id="visualizations"><b>Visualizations</b></h2>
The following visualizations were created during the project:

- <b>Age Distribution:</b> Histogram with KDE to illustrate age trends.
- <b>Sports Popularity:</b> Bar plot of sports frequency.
- <b>Medal Distribution by Age:</b> Box plot showing age trends across medalists.
- <b>Correlation Heatmap:</b> Relationships between Age, Height, and Weight.

<h2 id="key-insights"><b>Key Insights</b></h2>

### Age Trends:
- Most athletes are in their early 20s to mid-30s.
- Medalists exhibit a slightly different age range depending on the sport.
### Physical Characteristics:
- Height and Weight correlate strongly, as expected.
- Certain sports favor specific physical attributes (e.g., taller athletes in basketball).
### Missing Data:
- Missing values were mainly found in Age, Height, and Weight.
- Imputed values appropriately to ensure data consistency.

To take a deep look in the project you may check out my Kaggle notebook: <a href="https://www.kaggle.com/code/belizyazici/data-analysis-of-olympic-history" target="_blank" rel="noreferrer" style="color: #8e44ad;"> Data Analysis of 120 Years of Olympic History: Athletes and Results Dataset </a>
