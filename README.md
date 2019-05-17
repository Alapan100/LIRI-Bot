# LIRI-Bot

## concert-this:

![concert-this](/images/concert-this.jpg "Concert")

#### In the following example the user is looking for the next Taylor Swift Concert: node liri.js concert-this "Taylor Swift"

## Spotify-this-song:

![Spotify-this-song](images\Spotify-this-song.jpg "Song")

#### The 'Spotify-this-song' command uses the Spotify API to retrieve data about the song entered in the search parameter. All song titles that contain the search parameter or parts of it are returned. The user will receive the artist, song name, a link to preview the song, and the album name for each result. In this example the user is looking for the Song "Beauty and the Beast" node liri.js Spotify-this-song "Beauty and the Beast".

## Movie:

![Movie](images\Movie.jpg "Movie")

#### The 'movie-this' command uses the OMDb API to retrieve data about the movie entered in the search parameter. The result will include the title, release year, IMDb rating, Rotten Tomatoes rating, country or countries it was filmed in, language(s), plot, and actors/actresses in the film. In this example the user is looking for information about the movie "Nacho Libre" node liri.js movie-this "Nacho Libre".

## Do-what-it-says:

![D0-what-it-says](images\Do-what-it-says.jpg "Do what it says")

#### The 'do-what-it-says' command reads the random.txt file and executes the parameters inside of it. By default, it is set to 'Spotify-this-song, I Want It That Way', but this can easily be changed as needed.
