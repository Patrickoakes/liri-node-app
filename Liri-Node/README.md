                          LIRI APP!!!!
1. In this App I am going to develop a Language Interpretation and Recognition Interface(LIRI), it is intended to to be a command line node app that will allow you to check out your favorite bands and concerts, look up your favorite movie information, ratings, actors, and request songs to play from spotify.

2.Using a variety of NPM packages, such as axios, You will be able to access API nodes and stream contact from various websites.
3. a.`node liri.js concert-this <artist/band name here>`

      ----  This will search the Bands in Town Artist Events API (`"https://rest.bandsintown.com/artists/" + artist + "/events?app_id=codingbootcamp"`) for an artist and render the following information about each event to the terminal:

      ----  Name of the venue

      ----  Venue location

      ----  Date of the Event (use moment to format this as "MM/DD/YYYY")

2. `node liri.js spotify-this-song '<song name here>'`

      ----This will show the following information about the song in your terminal/bash window
      ---- Artist(s)
      ---- The song's name
      ---- A preview link of the song from Spotify
      ---- The album that the song is from

       ----If no song is provided then your program will default to "The Sign" by Ace of Base.



3. `node liri.js movie-this '<movie name here>'`

   * This will output the following information to your terminal/bash window:

     ```
       * Title of the movie.
       * Year the movie came out.
       * IMDB Rating of the movie.
       * Rotten Tomatoes Rating of the movie.
       * Country where the movie was produced.
       * Language of the movie.
       * Plot of the movie.
       * Actors in the movie.
     ```

   * If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'

     * If you haven't watched "Mr. Nobody," then you should: <http://www.imdb.com/title/tt0485947/>

     * It's on Netflix!


4. `node liri.js do-what-it-says`

   
     * It should run `spotify-this-song` for "I Want it That Way," as follows the text in `random.txt`.

     * Edit the text in random.txt to test out the feature for movie-this and concert-this.

4. Include screenshots, gifs or videos of the app functioning

5. Contain a link to a deployed version of the app

6. The technologies used in the app are the Node.js, NPM Axios, NPM moment, NPM DotEnv, package.json to access objects in API from Bands in town, OMDB, and spotify, node module, javascript, and vastly more.

7. Patrick Oakes developed the APP