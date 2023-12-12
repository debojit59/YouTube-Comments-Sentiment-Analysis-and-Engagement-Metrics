Summary:
This project focuses on analyzing YouTube comments using sentiment analysis and extracting engagement metrics from the dataset. The primary tasks include:

Data Cleaning:

The initial step involves reading a YouTube comments dataset (UScomments.csv) and handling missing values.
The textblob library is used for sentiment analysis, which requires textual data. Therefore, rows with missing comments are dropped.
Sentiment Analysis:

Sentiment analysis is performed on the remaining comments using the TextBlob library. The sentiment polarity of each comment is calculated, indicating the positivity or negativity of the text.
Word Cloud Visualization:

A Word Cloud is generated to visualize the most frequently occurring words in positive comments. The wordcloud library is employed for this purpose.
Emoji Analysis:

Emojis from the comments are extracted and their frequency is analyzed. The top 10 emojis are identified and plotted using seaborn and plotly.
Data Integration and Exploration:

Additional YouTube datasets (e.g., CAvideos.csv, DEvideos.csv) are integrated into a comprehensive DataFrame (full_df). Duplicates are removed, and the cleaned data is saved to CSV, JSON, and SQLite formats.
Likes Analysis by Category:
