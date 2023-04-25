# Spotify Top Tracks README.md

This Python program retrieves your top 50 Spotify tracks using the Spotify API and displays them on a Flask web app.
## Features
- OAuth2 Authentication with Spotify
- Retrieves the user's top 50 tracks for the medium term (approximately last 6 months)
- Displays the tracks along with the artist name and popularity
## Dependencies
- Python 3.6+
- Flask
- Requests
- Spotipy
## Configuration 
1. Create a new application on the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications)  to get your `client_id` and `client_secret`. 
2. Add a Redirect URI in your application's settings. This should match the `redirect_uri` specified in `config.ini`. 
3. Create a `config.ini` file in the project directory with the following content:

```makefile

[SPOTIFY]
client_id = YOUR_CLIENT_ID
client_secret = YOUR_CLIENT_SECRET
redirect_uri = YOUR_REDIRECT_URI
```



Replace `YOUR_CLIENT_ID`, `YOUR_CLIENT_SECRET`, and `YOUR_REDIRECT_URI` with the appropriate values from your Spotify Developer Dashboard.
## Installation
1. Clone the repository:

```bash

git clone https://github.com/yourusername/spotify-top-tracks.git
```


1. Change to the project directory:

```bash

cd spotify-top-tracks
```


1. Create a virtual environment and activate it:

```bash

python3 -m venv venv
source venv/bin/activate
```


1. Install the required packages:

```

pip install -r requirements.txt
```


## Usage
1. Start the Flask web app by running:

```

python app.py
```

 
1. Open your web browser and navigate to `http://localhost:7777`.
2. Click the "Login with Spotify" button to authenticate with your Spotify account.
3. The web app will display your top 50 tracks along with the artist name and popularity.
## License

This project is licensed under the MIT License. See the [LICENSE](https://chat.openai.com/LICENSE)  file for details.# spotify-top-tracks
