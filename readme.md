Please see the code in liri.js and screenshots for walk-through:

Liri Code 1 - Screenshot
    Listed variables for the required packages for the application. Also showing the switch statements which are used to filter a request. The app takes in parameters and gives you back a response based off the following parameters:
    "spotify-this-song" => To find out information of a song 
    "concert-this" => To find concert locations from artist you are searching
    "movie-this" => To find movie information from a movie you are searching
    "do-what-it-says" => Randomly generate information from an already generated request

Liri Code 2 - Screenshot
    Shows the code for Spotify function
        "spotify-this-song"

Liri Code 3 - Screenshot
    Shows the code for Bands In Town function 
        "concert-this"

Liri Code 4 - Screenshot
    Shows the code for OMDB function 
        "movie-this"

Liri Code 5 - Screenshot
    Shows the code for Random function 
        "do-what-it-says"

/////////////////////////////////////////////////////////////////////////

Liri Code with concert-this response:
    This will search the Bands in Town Artist Events API for an artist and render the following information about each event to the terminal:
        - Name of the venue
        - Venue location
        - Date of the Event (use moment to format this as "MM/DD/YYYY")

Liri Code with do-what-it-says response:
    LIRI will use the text from “random.txt” and call on of LIRI’s commands.
        Currently, it is set to Spotify-this-song for “I want it That way”.

Liri Code with movie-this response:
    This will output the following information to your terminal/bash window:
        - Title of the movie.
        - Year the movie was released.
        - IMDB Rating of the movie.
        - Rotten Tomatoes Rating of the movie.
        - Country in which the movie was produced.
        - Language of the movie.
        - A short plot of the movie.
        - Actors in the movie.

Liri Code with spotify-this-song response:
    This will show the following information about the song in your terminal/bash window
        - Artist(s)
        - The song's name
        -A preview link of the song from Spotify
        - The album that the song is from


