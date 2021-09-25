# Unit 4 Project: Twitter Client - Part 2

## Overview
Build a simple Twitter client that supports viewing a Twitter timeline and composing a new tweet.

### User Histories

User can sign in to Twitter using OAuth login

User can view the tweets from their home timeline

For each tweet, show the relevant information: the tweet body along with the author's username and name
 Creating the Timeline
 API Request and creating models
Sending Network Requests
 Showing the data with a RecyclerView
Using the RecyclerView

User can refresh tweets timeline by pulling down to refresh

User can compose a new tweet
 User can click a "Compose" icon in the AppBar on the top right
 User can then enter a new tweet and post this to twitter
 User is taken back to home timeline with new tweet visible in timeline
 Newly created tweet should be manually inserted into the timeline and not rely on a full refresh


### Stretch stories
User can view more tweets as they scroll with infinite pagination

Improve the user interface and theme the app to feel "twitter branded"

Links in tweets are clickable and will launch the web browser

User can select "reply" from detail view to respond to a tweet

Move the "Compose" action to a FloatingActionButton instead of on the AppBar.

Compose activity is replaced with a modal overlay

Use Parcelable instead of Serializable using the popular Parceler library.

User can open the twitter app offline and see last loaded tweets.

Tweets are persisted into sqlite and can be displayed from the local DB

When a user leaves the compose view without publishing and there is existing text, prompt to save or delete the draft.
If saved, the draft should then be persisted to disk and can later be resumed from the compose view.

<img src="twitter2-walkthrough.gif" width=250><br>

GIF created with [LiceCap](http://www.cockos.com/licecap/).

### Notes
I faced some challenges working in the implementation of my account of Twitter getting linked with this app.

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids


    Copyright 2021 Alvaroots97

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
