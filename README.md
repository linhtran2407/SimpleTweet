# SimpleTweet - Part 1
SimpleTweet is an Android app that allows a user to log in their Twitter accounts via OAuth login, compose new tweets, and view their Twitter timeline. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Language used: Java

## User Stories

The following **required** functionality is completed:

- [x] User can **sign in to Twitter** using OAuth login
- [x]	User can **view tweets from their home timeline**
  - [x] User is displayed the username, name, and body for each tweet
  - [x] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
- [x] User can refresh tweets timeline by pulling down to refresh

The following **optional** feature is implemented:

- [x] User can view more tweets as they scroll with infinite pagination

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='simpletweet1_walkthrough.gif' title='Video Walkthrough SimpleTweet 1' width=250><br>

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

# SimpleTweet - Part 2

SimpleTweet is an Android app that allows a user to view their Twitter timeline and post a new tweet. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

## User Stories

The following **required** functionality is completed:

- [x] User can **compose and post a new tweet**
  - [x] User can click a “Compose” icon in the Action Bar on the top right
  - [x] User can then enter a new tweet and post this to twitter
  - [x] User is taken back to home timeline with **new tweet visible** in timeline
  - [x] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='simpletweet2_walkthrough.gif' title='Video Walkthrough SimpleTweet 2' width=250><br>

## License
This is a CodePath Android development course.
