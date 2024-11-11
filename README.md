### Project Overview: Zomato Data Analysis

This project analyzes data from a Zomato dataset to uncover key insights into restaurant trends, customer preferences, and other attributes. Various Python libraries, including `pandas`, `numpy`, `matplotlib`, and `seaborn`, were used to clean, process, and visualize the data effectively.

### Key Components of the Code:

1. **Data Preparation:**
   - Loaded the Zomato dataset using `pandas`.
   - Displayed the initial structure using `df.head()` and checked for missing values with `df.isnull().sum()`.

2. **Data Cleaning:**
   - Applied a custom function `handleData()` to clean and convert restaurant ratings stored in an inconsistent format to float.

3. **Visualizations and Insights:**
   - **Restaurant Type Distribution:** Created a count plot to show the distribution of restaurant types (`sns.countplot`), revealing that most restaurants fall into the dining category.
   - **Votes by Restaurant Type:** Grouped data by restaurant type to sum up votes, visualized using a line plot. It highlighted that dining restaurants received the most votes.
   - **Restaurant with Maximum Votes:** Extracted and printed the name of the restaurant(s) with the highest votes.
   - **Online Order Analysis:** A count plot indicated that the majority of restaurants do not accept online orders.
   - **Rating Distribution:** A histogram was plotted to show the distribution of restaurant ratings, with most ratings between 3.5 and 4.
   - **Approximate Cost Analysis:** Visualized with a count plot, showing that a large number of restaurants have an approximate cost of 300 rupees for two people.
   - **Online Order vs. Rating:** Created a box plot that demonstrated higher ratings for online orders compared to offline orders.
   - **Order Mode by Restaurant Type:** A heatmap from a pivot table highlighted the preference for offline orders at dining restaurants and online orders at cafes.

### Conclusions Drawn:
- **Dining Preference:** The majority of restaurants analyzed fall into the dining category, which also attracts more customer votes.
- **Top Restaurant by Votes:** "Empire Restaurant" was found to have the highest number of votes.
- **Online Order Insights:** Most restaurants do not offer online ordering, but those that do receive higher ratings on average.
- **Cost Preferences:** A significant number of couples prefer dining in places with an approximate cost of 300 rupees.
- **Ordering Trends:** Offline orders are favored at traditional dining spots, while cafes see a trend towards online ordering.

This analysis provides actionable insights into customer preferences and restaurant trends in the dataset.
