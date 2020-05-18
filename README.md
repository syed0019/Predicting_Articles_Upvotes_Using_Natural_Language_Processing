## Predicting_Articles_Upvotes_Using_Natural_Language_Processing
**_[Hacker News](http://news.ycombinator.com/)_** is a community where users can submit articles, and other users can upvote those articles. The articles with the most upvotes make it to the front page, where they're more visible to the community.

Our dataset consists of submissions users made to Hacker News from 2006 to 2015. Moreover, we have sampled `3000` rows randomly from [here](https://github.com/arnauddri/hn) and we removed all of the extraneous columns. Our data only has four columns:

- `submission_time` - When the article was submitted
- `upvotes` - The number of upvotes the article received
- `url` - The base URL of the article
- `headline` - The article's headline

In this mission, we'll be predicting the number of upvotes the articles received, based on their headlines. Because upvotes are an indicator of popularity, we'll discover which types of articles tend to be the most popular.
