# Google Play Store Data Analysis (EDA)

This repository contains a comprehensive analysis of the **Google Play Store Apps** dataset, which includes **10,841 rows** and **14 columns**. The dataset provides insights into various aspects of apps on the Google Play Store, such as ratings, reviews, installs, size, price, and more. The goal of this analysis is to explore the data and uncover trends and patterns that can be useful for understanding the app market.

---

## Dataset Information

The dataset consists of the following **14 columns**:

1. **Index**: Row index for the dataset.
2. **App**: The name of the app.
3. **Category**: The category of the app (e.g., Game, Tools, Education).
4. **Rating**: User ratings of the app (out of 5).
5. **Reviews**: The number of reviews the app has received.
6. **Size**: The size of the app (in bytes).
7. **Installs**: The number of times the app has been installed.
8. **Type**: The type of the app (free or paid).
9. **Price**: The price of the app (0 for free apps and the actual price for paid apps).
10. **Content Rating**: The content rating for the app (e.g., Everyone, Teen, Mature).
11. **Last Updated**: The date when the app was last updated.
12. **Current Version**: The current version of the app.
13. **Android Version**: The minimum Android version required for the app.
14. **Unnamed: 0**: This column serves as an identifier and is necessary for the analysis.

---

## Data Source

The dataset used in this analysis can be downloaded from Kaggle:

[Kaggle - Google Play Store Apps Dataset](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

---

## Requirements

The following libraries are used for data cleaning, analysis, and visualization:

- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualization.
- `seaborn`: For statistical data visualization.

You can install the required libraries using:

```bash
pip install pandas matplotlib seaborn
