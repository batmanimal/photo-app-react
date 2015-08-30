## My Super Awesome Photos 
###Photo album app built using React

Design mock (from my Angular version, see below for links)

![design](http://i.imgur.com/EygN6p7l.jpg)

### Component Hierarchy

Inspired by the excellent ["Thinking in React"](http://facebook.github.io/react/docs/thinking-in-react.html) tutorial, here is the hierarchical organization of components I will build, based on the mock:

- `AppHeader` (displays static header)
- `AppContainer` (contains entire app under header)
    * `SelectedPhoto` (displays the selected photo)
    * `PhotoInfo` (displays caption and count for the selected photo)
    * `AlbumInfo` (displays photo list)
        - `PhotoListHeader` (displays a heading for the album)
        - `PhotoTitle` (displays a clickable photo title)
    - `RatingDropdown` (receives user input to rate the photo in the display) 
    - `RatingDisplay` (displays the star value under the dropdown) <- not shown in the mock

### Process

1. Build the static version (includes all the UI components I listed above that do not contain interactivity or state)
  - `AppContainer`
  - `AppHeader` (just HTML with Bootstrap)
  - `AlbumInfo` (table that holds list)
  - `PhotoListHeader` (displays a heading for the album)      
  - `PhotoTitle` (displays a clickable photo title)
  - `RatingDropdown` (menu with 4 options)

2. Build the interactive components [TODO]

### Dependencies

- react 
- JSXtransformer
- react-bootstrap
- bootstrap 

### Related Projects

- Check out the same app implementation in [Angular](https://github.com/batmanimal/photo-app-angular)
- Check it out in [Backbone](https://github.com/batmanimal/photo-app-backbone)

