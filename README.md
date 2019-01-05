# GREENLIGHT

<p align="center">
<img align="center" src="/assets/img/GreatDay.png" width="100%"/>
</p>

## SPOTIFY AND BANDSINTOWN API
This app utilizes the Spotify and Bandsintown API to allow users to search for music, bandsintown, tour dates, and turn your computer into remote speakers for Spotify.
Please note that the Spotify API only provides 30 second audio snippets. It may be possible to get the full track by using the [Web Playback SDK](https://beta.developer.spotify.com/documentation/web-playback-sdk/).

## YOUR GREENLIGHT ACCESS
Click here for your [GREENLIGHT](http://github.com/bootcampgreenlight.herokuapp.com) access.

## THE SDKs STRUCTURE

The Spotify SDK consists of two libraries.
One of them handles authentication flow and the other one manages audio playback.
The libraries work well together but can also be used separately, for example if
the application doesn't need to play music it can use just Spotify Authentication module by itself.

SPOTIFY AUTHENTICATION LIBRARY
------------------------------

This library is responsible for authenticating the user and fetching the access token
that can subsequently be used to play music or be used in requests to the Spotify Web API.

SPOTIFY PLAYER LIBRARY
----------------------

This library can play music from Spotify after the user logs in with the access token.
**Only Spotify account users will be able to log in and play music with this library.**.

## CREDITS

 - [ChereeNielson](https://github.com/ChereeNielson) for [all front end design](https://github.com/sayex/Project1/tree/chereehtml)
 - [EricSayex](https://github.com/sayex) for [APIs, back end design, and Heroku hosting](https://github.com/sayex/Project1/tree/ericbranch)
 - [StanBakalov](https://github.com/sunnybakalov) for [APIs and back end design](https://github.com/sayex/Project1/tree/stansBranch)