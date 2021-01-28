# Automate Spotify playlist from Youtube

## Instructions
  
1. Install all dependencies

`pip3 install -r requirements.txt`

2. Collect You Spotify User ID and Oauth Token From Spotfiy and add it to secrets.py file

To Collect your User ID, Log into Spotify then go here: [Account Overview](https://www.spotify.com/us/account/overview/) and its your Username alt text
To Collect your Oauth Token, Visit this url here: [Get Oauth](https://developer.spotify.com/console/post-playlists/) and click the Get Token button alt text
Enable Oauth For Youtube and download the client_secrets.json

3. Run the File

`python3 create_playlist.py`
