# Project 2 - *Twitter Client - Part 2*

**Twitter** is an android app that allows a user to view his Twitter timeline and post a new tweet. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **15** hours spent in total

## User Stories

The following **required** functionality is completed:

- [X] User can **compose and post a new tweet**
  - [X] User can click a “Compose” icon in the Action Bar on the top right
  - [X] User can then enter a new tweet and post this to twitter
  - [X] User is taken back to home timeline with **new tweet visible** in timeline
  - [X] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh
  - [X] User can **see a counter with total number of characters left for tweet** on compose tweet page

The following **optional** features are implemented:

- [X] User is using **"Twitter branded" colors and styles**
- [X] User can click links in tweets launch the web browser 
- [ ] User can **select "reply" from detail view to respond to a tweet**
- [ ] The "Compose" action is moved to a FloatingActionButton instead of on the AppBar
- [ ] Compose tweet functionality is build using modal overlay
- [ ] Use Parcelable instead of Serializable using the popular [Parceler library](http://guides.codepath.org/android/Using-Parceler).
- [X] User can **open the twitter app offline and see last loaded tweets**. Persisted in SQLite tweets are refreshed on every application launch. While "live data" is displayed when app can get it from Twitter API, it is also saved for use in offline mode.
- [ ] When a user leaves the compose view without publishing and there is existing text, prompt to save or delete the draft. If saved, the draft should then be **persisted to disk** and can later be resumed from the compose view.
- [ ] Enable your app to receive implicit intents from other apps. When a link is shared from a web browser, it should pre-fill the text and title of the web page when composing a tweet. 

The following **additional** features are implemented:

- [X] List anything else that you can get done to improve the app functionality!
  -  [X] Circle Image View

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<table width="600" border="0">
  <tr>
    <td> <strong><underline>Walkthrough 1</underline></strong> <p> <img src='SimpleTweet2.gif' title='Twitter part II' width='' alt='Twitter 2' /></td>
    <td> <strong><underline>Character count 1</underline></strong> <p>  <img src='Count2.gif' title='Twitter part II-Counter2' width='' alt='Design 2' /></td>
    <td> <strong><underline>Character count ALT </underline></strong> <p> <img src='Count1.gif' title='Twitter part II-Counter1' width='' alt='Design 1' /></td>
    <td><strong> <u>Offline</u> </strong> <p> <img src='Offline.gif' title='Twitter part II-Offline' width='' alt='Offline' /></td>
  </tr>
 </table>



GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

<strong>Describe any challenges encountered while building the app.</strong>
  - [X] Crashing
  - Implementing color schemes
  - Counter not working as intended.

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
