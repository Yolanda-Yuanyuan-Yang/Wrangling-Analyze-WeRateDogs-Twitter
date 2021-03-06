**Udacity Data Analysis Project &mdash; WeRateDogs Tweet Archive Wrangling, Tweepy API Integration, and Analysis** \
 \
In this project, data exploration, wrangling, analysis and visualization was conducted on a tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs has over 4 million followers and has received international media coverage. \
\
WeRateDogs downloaded their Twitter archive, which is made available by Udacity. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. As a part of this project, the basic tweet data from the archive was supplemented using the Tweepy API to capture additional information by a direct connection to Twitter. \
 \
Additionally, Udacity ran every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs. The results were a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images). These predictions were also supplied by the Udacity Data Analysis nanodegree program. \
 \
This project repository includes the following materials:
- twitter_archive_enhanced.csv &mdash; This is the Twitter archive data from WeRateDogs, which was supplied as a part of the academic materials from the Udacity Data Analysis nanodegree program.
- image-predictions.tsv &mdash; The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. THis was also supplied by the Udacity Data Analysis nanodegree program.
- wrangle_act.ipynb &mdash; This is the Jupter notebook documention, where code, visualizations and narrative texts were created.
- twritter_archive_master.csv &mdash; This is the CSV file with the cleaned and supplemented data after activities performed in this project.
- twitter_json.txt &mdash; Storage of each tweet's entire set of JSON data acquired using the Tweepy API.
