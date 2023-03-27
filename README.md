# Sub-Reddit-Pipeline
The project goal is to practice building Data Engineering pipeline in my local for learning. 
I tried to extract/scrap data from sub-reddit for given handle and tranform via pandas in python and load the data in psql

## My Goal:
My Goal was to go to "https://www.reddit.com/r/dataengineering/
And collect all post for a week and provide most upvoted post url for last week.

### Step 1:
To do that I had to load the page via Selenium and scroll the data until I get atleast "8 days ago" old post data

### Step2:
Then I had to dowload the source code and use BeautifulSoup to parse and collect required info (title, upvote, link, post_date)

### Step3:
Then I did tranformation in Python using Pandas lib

### Step4
And loaded the data to psql in my local

-----------------

Please check out the upload Jupyter notebook file to know how I did them.

Feel free to suggest on improvements.

Thanks
