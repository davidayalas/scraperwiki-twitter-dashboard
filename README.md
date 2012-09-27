Python code to execute inside Scraperwiki (https://scraperwiki.com) and get a dashboard of twitter users listed in usernames array:

*	Modify array to get your own users:

			usernames = ["user1","user2","user3"];

*	Once your script is executed, you can consume data throught its api:

			https://api.scraperwiki.com/api/1.0/datastore/sqlite?format=jsonlist&name=twitter_dashboard&query=select%20*%20from%20%60swdata%60

*	Live scrapper

			https://scraperwiki.com/scrapers/twitter_dashboard/ 