## Photo Album App, built using React

Design mock (taken from the completed version in Angular)

![design](http://i.imgur.com/EygN6p7l.jpg)

### Component Hierarchy

Inspired by ["Thinking in React"](http://facebook.github.io/react/docs/thinking-in-react.html), here is the organization of each component in the mock:

- `AppHeader` (displays static header)
- `AppContainer` (contains entire app under header)
    * `SelectedPhoto` (displays the selected photo)
    * `PhotoInfo` (displays caption and count for the selected photo)
    * `AlbumInfo` (displays photo list)
        - `PhotoListHeader` (displays a heading for the album)
        - `PhotoTitle` (displays a clickable photo title)
    - `RatingDropDown` (receives user input to rate the photo in the display) 
    - `RatingDisplay` (displays the star value under the dropdown) <- not shown in the mock


### Process

1. Build the static version (UI components without interactivity)

  -  `AppHeader` (just HTML with Bootstrap)
  -  `AlbumInfo` (table that holds list)
     - `PhotoListHeader` (displays a heading for the album)      
     - `PhotoTitle` (displays a clickable photo title)
  -  `RatingDropDown` (menu with 4 options)

### Related Projects

- Check out the same app implementation in [Angular](https://github.com/batmanimal/photo-app-angular)
- Check it out in [Backbone](https://github.com/batmanimal/photo-app-backbone)

