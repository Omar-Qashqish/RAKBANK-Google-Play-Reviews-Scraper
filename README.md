# 📱 RAKBANK Google Play Reviews Scraper

This Python script collects user reviews of the RAKBANK mobile app from the Google Play Store using the `google-play-scraper` library.

---

## ✅ What the Script Does

- Scrapes **written reviews**.
- Collects reviews in **both Arabic and English**.
- Merges all reviews into one combined dataset.
- Saves the result to a **CSV file** and a **pandas DataFrame** for further use.

---

## 📤 Output

The script outputs a file named:
rakbank_reviews_all.csv


It also creates a pandas DataFrame named:
df_all


---

## 📊 DataFrame Contents

Each row in the DataFrame includes:

| Column         | Description                                 |
|----------------|---------------------------------------------|
| `Name`         | Name of the user who submitted the review   |
| `Comment`      | The actual review text                      |
| `Rating`       | The star rating (1 to 5)                    |
| `Language`     | Language of the review (`ar` or `en`)       |

---

This script is useful for analyzing customer feedback on the RAKBANK mobile app directly from Google Play.



