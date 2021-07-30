# Mobile Developer Challenge

## App Challenge

Create an iOS or Android application that retrieves data over the network and displays for the user

The app should be written in Swift **or** Kotlin.

The app will be using [The Movie Database API](https://www.themoviedb.org/documentation/api).

Steps to get API Key:
- Signup for an account
- Verify Email address
- Sign in and go to: https://www.themoviedb.org/settings/api
- Click on `Generate a new API key`. Generate the API Key type as `Developer`
- Follow steps and fill out any information needed.

**Note:** You are free to use any libraries you see fit for this project, though you may be asked about their use.

We would like the app to display:

#### Main Screen
- Home Tab:
  - This section is divided into upper and lower, each containing a horizontal carousel. The upper carousel should display `Now Playing` movies and the lower carousel display `Most Popular` movies. Each item should display a thumbnail and title of the movie. Items in both carousels should be clickable and trigger the Movie Details Screen.

- Favorites Tab:
  - Displays a list of the movies that a user has marked as 'favorites'. This list should be persisted for viewing even when offline. A list item should be clickable and trigger Movie Details Screen. A user should be able to remove a movie from their favorites list.

#### Movie Details Screen
- Display the movie poster
- Display pertinent details for the specific movie including title, genre(s), release date, rating, overview.
- Provides a button that allows a user to save this movie to their favorites list.


## Submitting

Please provide a github repository.
