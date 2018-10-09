# C2C_bootcamp_start

We will use this project as a base for our C2C bootcamp exercises. It is based on the code from [Spotify Web API authorization examples](https://github.com/spotify/web-api-auth-examples). In the app.js we are using the code for tge authorization code method.
This project contains basic demos showing the different OAuth 2.0 flows for [authenticating against the Spotify Web API]

The places where you need to insert code are marked by comments and will be also mentioned during the bootcamp.

## Installation

This project requires node.js to be installed on your machine.

After cloning the repository, install its dependencies running:

    $ npm install

### Using your own credentials
You will need to register your app and get your own credentials from the Spotify for Developers Dashboard.

To do so, go to [your Spotify for Developers Dashboard](https://beta.developer.spotify.com/dashboard) and create your application. This is the Redirect URI we will be using for our application:

* http://localhost:8888/callback

Once you have created your app, replace the `client_id` and `client_secret` in the app.js with the ones you get from My Applications. Also the callback needs to be registered with the application on the developer account.

## Running the app
In order to run the app, open the `spotify_app` folder and run `app.js` in the following manner: 

    $ cd spotify_app
    $ node app.js

Then, open `http://localhost:8888` in a browser.
