# Unit 1 Project: *Flixster - Part 1* 

**Flixster** Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

Submitted by: **Fola**

Time spent: **~5.54** hours spent in total

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

---

## Flix Part 1

### User Stories
The following **required** functionalities are completed:

#### REQUIRED (10pts)
- [X] (10pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [X] (2pts) Views should be responsive for both landscape/portrait mode.
   - [X] (1pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [X] (1pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

- [ ] (2pts) Display a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [X] (2pts) Improved the user interface by experimenting with styling and coloring.
- [ ] (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

## App Walkthrough

Here's a walkthrough of app:

<img src='FlixsterP.gif' title='Flixster Walkthrough' width='' alt='Flix in portrait mode' />

<img src='FlixsterL.gif' title='Flixster Walkthrough' width='' alt='Flix in landscape mode' />

IMGUR: https://imgur.com/CN7tWo1

IMGUR: https://imgur.com/Y6SgenC

GIF created with [ScreenToGif](https://www.screentogif.com/).

### Notes
Describe any challenges encountered while building the app.

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids

## Notes

Experienced "Invalid Gradle JDK configuration found. Open Gradle Settings Change JDK location" error; it was resolved by changing plugin version & eventually deleting .idea/gradle.xml & .idea/workspace.xml files.

## License

    Copyright 2021 AOI Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

