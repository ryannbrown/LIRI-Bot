# LIRI-Bot


## Liri-Bot-Application
This app is going to search for a song, movie and a band's schedules using Node.js. LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

## How the app works
The app Liri works by on the command line off of Node.js. These are the phrases that are used to invoke LIRI: -node liri.js for searching for any movie info using omdb api, -node liri.js to get info on song using Node Spotify API npm package and finally -node liri.js <band/artist name> to get the dates and venues of music concerts of your chosen artist or band.

## Technology used
Javascript and node.js

### Required packages
-Axios -Node-spotify-api

### APIs used
Bands in Town Artist Events API
OMDB API

# Instructions

## Step 1 (install packages)

First of all, we need to install the correct npm packages. For each of the packages that we are requiring at the top of our code, we need to NPM Install them in the terminal when navigated to liri.js. This will enable to us to utilize the npm packages implemented in the code so that we can get the information we are requesting. We need to install the packages Dotenv, Node-Spotify-app, as well as Moment.js (Below is example for installing a package)


![Capture](https://user-images.githubusercontent.com/44414542/57199062-d5fd8180-6f48-11e9-85e6-c1d7e79fc101.PNG)

## Step 2 (Search Concert)
Below is the command we use to search for a particular band's upcoming concert information. This searches through the bands in town api and returns strings related to topics given
![image](https://user-images.githubusercontent.com/44414542/57199479-3f7f8f00-6f4d-11e9-89e1-d551a1f4b65a.png)

If no error occurs, we will see the string "This is loaded" as well as information for all of the upcoming concerts 

![image](https://user-images.githubusercontent.com/44414542/57199488-5e7e2100-6f4d-11e9-826b-f7aa49b16966.png)

## Step 3 (Search Movie)
Below is the command we use to search for a particular movie. This searches through the omdb api and returns strings related to topics given.
![image](https://user-images.githubusercontent.com/44414542/57199444-ef083180-6f4c-11e9-9290-34769dd896bf.png)


If no error occurs, we will see the string "This is loaded" as well as the information for requested movie
![image](https://user-images.githubusercontent.com/44414542/57199467-270f7480-6f4d-11e9-98d3-8da7ec62952a.png)

## Step 4 (Search Song)
Below is the command we use to search for a particular song. This searches through the Spotify API and returns strings related to topics given

![image](https://user-images.githubusercontent.com/44414542/57199502-9d13db80-6f4d-11e9-8b1a-377d678bc072.png)


If no error occurs, we will see the string "This is loaded" as well as the information for each song.

![image](https://user-images.githubusercontent.com/44414542/57199510-b61c8c80-6f4d-11e9-9481-1245099b8a41.png)

## Conclusion
So there you have it. This is a backend app that can be used to search for concert, song, and movie information. Enjoy! 




