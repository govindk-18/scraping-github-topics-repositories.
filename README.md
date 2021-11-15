# scraping-github-topics-repositories.

![](https://i.imgur.com/uk47YQz.png)

Summary of what I did
![](https://i.imgur.com/Ol3Gud5.png)

-So I have scraped the top 30 topics from https://github.com/topics.

-I got the username,repo name, stars & url from top repos from the individual topic

-I have created created seperate csv file for each topic which provides in-depth information about the topics

Drawbacks
- Only the frust 30 repos were scraped, more can be done by using "?page=" the desired page number.
- The BeautifulSoup librabry is a simple library, will run into issues for websites with a loading screen.
