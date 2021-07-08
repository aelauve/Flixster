# Flixster

Flixster is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flixster Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [x] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="http://g.recordit.co/PwiKTukgvq.gif" width=250><br>

### Notes
I spent a large amount of time trying to apply constraints to the details page. This is currently a work in progress as I continue to research possible solutions.

---

## Flixster Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [x] (2pt) User can view the app on various device sizes and orientations.
- [] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="http://g.recordit.co/SdCl6wNYNH.gif" width=250>
<img src="http://g.recordit.co/city9Y6mgB.gif" width=500><br>
<img src="http://g.recordit.co/qyl5tGoi18.gif" width=250>




### Notes
I had some minor difficulty in installing the Pod and getting it to work correctly in Xcode. I was able to resolve it by utilizing the "Fix" feature's suggestions. I also struggled with AutoLayout, specifically understanding the errors about positioning. I came to realize that it is not only important to give constraints based on position, but that some components would also require constraints for width or height in order for the layout to work.
