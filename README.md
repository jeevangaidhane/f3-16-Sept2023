# OMDB-Movie-Search-Dashboard-With-Error-Handling
UI Reference

Project Overview- OMDB Movie Search Dashboard With Error Handling
UI Reference

Figma Link- https://www.figma.com/file/K8tGKTL6tSFENvCBtBjyTy/F3---OMDB?type=design&node-id=0%3A1&mode=design&t=Ac2Rw9D1xECoHnGe-1

Task Description
Design an interactive movie search dashboard using the OMDB API. The dashboard should include two distinct input fields: one for the API key and another for the movie's title. Users should be able to retrieve a list of movies that matches their search query by clicking on a singular "Search" button. Additionally, during the data fetching process, showcase a custom spinning loader to enhance user experience. Ensure the application is user-friendly and responsive.
To interface with the OMDB API, use the endpoint: https://www.omdbapi.com/?s={SEARCH_TERM}&apikey={API_KEY}. To secure an API key, sign up at OMDB API.
From the returned data, focus on the following:

Search: Array encapsulating movie details: - Title: Movie title. - Year: Release year. - imdbID: Unique movie identifier. - Type: Specifies if it's a movie or series. - Poster: URL to the movie poster.

Features
Inputs & Search: Integrate two input fields:
API Key input
Movie title input
Ensure both fields aren't empty before proceeding. Use a single "Search" button to initiate the search.

Custom Spinning Loader: During the data fetching phase, exhibit a CSS-based spinning loader. This loader should be hidden once data is successfully fetched or if an error occurs.

Movie Results: For each located movie, dynamically display a card illustrating:
The movie's poster
The title and its release year
A "More Details" option linking to IMDB using `imdbID`

Error Management: In situations where errors arise (like "Invalid API Key!"), relay meaningful feedback to users.

Adaptive Design: Ensure the dashboard's optimal performance across mobile and desktop.
Hints
For obtaining an API key, visit [OMDB API](https://www.omdbapi.com/apikey.aspx) and remember to adhere to rate limits.
Use the "Response" and "Error" keys in the API's returned JSON to manage errors effectively.
To craft the spinning loader, CSS keyframes will be instrumental. Research on "CSS Spinners" for inspiration.
Marking Scheme
Inputs & Search Mechanism - 35 Points
Construct two distinct input fields and ensure proper validation
Use a singular "Search" button to kickstart the process
Fetch and process the data effectively

Custom Spinning Loader - 20 Points
Design a spinning loader using pure CSS
Handle the show/hide mechanism of the loader appropriately

Displaying Movie Results - 30 Points
Generate dynamic movie cards with relevant attributes
Illustrate the correct movie poster and provide an IMDB link
Manage scenarios where the poster URL is "N/A"

Error Management - 10 Points
Implement error messages, emphasizing the "Invalid API Key!" scenario

Responsive Layout - 5 Points
Guarantee a seamless layout transition between devices