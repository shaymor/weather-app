# weather-app
This is a weather app I made whole learning Node.js.

The app uses [weatherstack](https://weatherstack.com/) for real time weather data and [Mapbox](https://www.mapbox.com/) to get coordinates based on an address or landmark name.

You can acccess a deployed version of this website at https://shamor-weather-app.herokuapp.com/.

# Running the application
1. Install the latest version of Node.js® via the [download page](https://nodejs.org/en/download/).
2. Clone this repository by running `git clone https://github.com/shay-m/weather-app.git` or downloading it via a Github client.
3. Navigate to root directory by running `cd weather-app` in the directory that you downloaded or cloned the project.
4. Rename the `.env.example` file to `.env` and fill in the values with your tokens.
  
   **Note:** You can get your API keys for both [Mapbox](https://www.mapbox.com/) and [weatherstack](https://weatherstack.com/) by going to their websites and creating an account.              A basic free account should have enough API calls for testing purposes.

5. Run `npm install` to install all the dependencies.
6. Run `npm start` to start the application.
7. Head to http://localhost:3000 to access the application.
