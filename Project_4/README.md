## Gathering the Data:
The data for this project was in three different formats:
1. `Twitter Archive File — WeRateDogs`: WeRateDogs downloaded their Twitter archive and shared it exclusively for use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.
2. `Image Prediction File`: The tweet image predictions, i.e., what breed of dog is present in each tweet according to a neural network is stored in this file. It was hosted on Udacity’s servers in tsv format.
3. `Twitter API — JSON File`: By using the tweet IDs in the WeRateDogs Twitter archive, I queried the Twitter API for each tweet’s JSON data using Python’s tweepy library.

## Assessing the Data
After gathering the data, the three tables were saved and assessed Visually and Programmatically. With both the assessments I looked for Unclean data in all the three DataFrames, i.e. for Tidiness and quality issues.

**Quality:** Low quality data is commonly referred to as dirty data. Dirty data has issues with its content. The Data Quality Dimensions are Completeness, Validity, Accuracy and Consistency.

**Tidiness:** Untidy data is commonly referred to as “messy” data. Messy data has issues with its structure. Tidy data is where:
* Each variable forms a column.
* Each observation forms a row.
* Each type of observational unit forms a table.

## Cleaning the Data
I followed the programmatic Data Cleaning process i.e. **Define**, **Code** and **Test**. I converted my observations from the assess step into defined problems, translated these definitions to sophisticated code to fix these problems, then tested the three datasets to make sure the operations worked.

## Analyzing the Data
Using this freshly cleaned WeRateDogs Twitter data, interesting and trustworthy analyses and visualizations were created to communicate back the findings.

