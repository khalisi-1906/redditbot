# redditbot
This project is a Reddit bot which gives COVID-19 stats of a specific region to Redditors based on their post title. It was created as a submission to the PESU HackerSpace SpaceJam 2021 hackathon. Out of ~120 teams, placed Top 5 Freshers' Track and Top 15 overall.

To get it up and running:

add the PRAW library to Python (3.6+), using pip install praw.
navigate to the Python folder, enter Lib folder, site-packages, and then open praw.ini
add a bot, like shown below:
[bot1]
client_id=
client_secret=
password=
username=
user_agent=<any name>
Note: covibot is designed to run in r/SpaceJam2021, a subreddit I created for testing covibot. By changing the line subreddit = r.subreddit("SpaceJam2021"), the bot can be deployed pretty much anywhere.

