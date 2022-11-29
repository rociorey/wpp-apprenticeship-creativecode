## **Traffic Jams**

Traffic Jams is merges the Spotify API with a Microsoft Traffic API so those in traffic jams can musically jam together through conjoint Spotify playlists.

------



##### About the code

- Written in Python
- Libraries: Spotipy, geocoder



##### How it works

- App gets current London traffic accidents and focuses on severe congestions
- A playlist for each congestion coordinate is created
- App gets user's geolocation and if it they are listening to a song in Spotify and their location matches a traffic jam, their song gets added to the shared Spotify playlist in that locations