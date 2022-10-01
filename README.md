INTRODUCTION

The objective of this project was to gather, clean and analyze over 5000+ tweets from the twitter account
of @dog_rates (WeRateDogs), draw some insights and make visualizations to communicate one of the
insights drawn. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment
about the dog. The account was started in 2015 by college student Matt Nelson, and has received
international media attention both for its popularity and notoriety.

The data wrangling process contains three major steps, namely:

• Gathering Data

• Assessing Data

• Cleaning Data

During this project, we will gather data belonging to Twitter user @dog_rates from a variety of sources
and in different formats, assess its quality and tidiness, then clean it.

PROJECT DATA

In this project, three datasets were indicated to be necessary for analysis.
• One was provided beforehand (twitter_archive_enhanced.csv), we downloaded this file and read
it in as a CSV file in a Pandas DataFrame using the pandas' read_csv function.
• The second file (image-predictions.tsv), i.e., what breed of dog (or other object, animal, etc.) is
present in each tweet according to a neural network was to be downloaded programmatically
using the 'requests' library and then stored into a file on the pc before being read into a Pandas
DataFrame using the read_csv function.
• The third file proved difficult to gather, it required applying for Twitter Developer access which I
applied for but I didn’t get the approval even after waiting for over a week. Thoughtfully Udacity
had an alternative option to this which involved downloading a provided tweet-json.text file and
reading the file line by line.

This Project was completed by Egwuda Ojonugwa Everest
