# Spotify Album Collage

![Image collage](collages/start_collage.jpeg)

### Contents
- collage.ipynb
  - Jupyter Notebook that creates the collage
  - Saves files locally
- collage.ipynb
  - tryna add opportunity to setup the grid
  - or make auto grid setup according by your album count

### About
A program that creates an image collage from album covers that you've saved before. Thanks that the author of original repo exists, because i spent some time on searching ready-to-use solutions and it was the best one - i only gave some changes in using Spotify-API, and ...

In the future i want to add some research elements to that program or matching close album covers in the picture by colour, and maybe add random on selecting covers (additional option)



### Current Functionality
- User can generate a basic collage in the notebook(1/2 version)

### Instructions on Using Jupyter Notebook
- Export the following environment variables (import os library):
  - SPOTIFY_CLIENT_ID
  - SPOTIFY_CLIENT_SECRET
  - SPOTIFY_REDIRECT_URI
- Run `jupyter notebook collage.ipynb` in command line

### How to get access --- Spotify API
1. Authorize in spotify for devs and go [here](https://developer.spotify.com/dashboard/create)
2. Create an app - just enter random name, in that case only "redirect URIs" matters, [here's hint](https://developer.spotify.com/documentation/web-api/concepts/apps)
3. eg, mine is "http://localhost:8888/callback", it will be a future redirect uri variable
4. after creation go to the settings of the app - here you can get a client ID and client secret - those two variables like a key of API.