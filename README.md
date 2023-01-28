# Movie-App
Create a Movie app by using simple HTML and CSS and JavaScript, fetching titles, posters, vote ratings, and overviews from themoviedb.org API. 

  . Create a folder named Movie App, inside that create files named "index.html", style.css, and script.js and attach it to the index.html file.

  . We create a header and main block elements.

  . In the header element, we create a form and input tag for the search bar.

  . And We create the main id in the main tag and create 'div' with a class name of movie which contains img, movie-info, and overview init.

  . We use style as per our wish to style our class movie to look like a card.

  . We use the transform translate css properties to make our overview dynamic on the card.

  . To add functionality we will use Javascript and bring all the required things we need from DOM using get Element By ID.

  . We make use of the moviedb API url and api-key, and create urls for popular movie lists and search movies based on searchTerm.

  . We fetch by using Async and Await functions.

  . And destructure all the required components such as title, poster_path, vote_average, overview in class name movie and use them in innerHTML.

  . Write a function for vote_average based on rating score to change color for ratings.

  . And Finally add an event listener in the id form to prevent default and to get movies based on the searchTerm.
