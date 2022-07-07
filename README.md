# Spotify Color 

#### (Brief Description of Application)
This application allows the user to login and access specific elements from their Spotify account (such as playlists, top artists, top tracks), and start a full screen visualizer that specifically plays a color array depending on our personal music information.   

#### By Alex Shevlin, Seung Lee, Caroline Cerussi, Donovan Weber, Jacob Palaoro

## Technologies Used

* _HTML_
* _CSS/Bootstrap_
* _Javascript/Jquery_
* _Markdown_
* _Node.JS_
* _See **package.json** for full list of dependencies._

## Description
The webpage opens to a login options for a user to enter their Spotify account information. Upon login, button options allow the user to navigate to the specific top artists, top albumns, and top playlists. From there, a table with a grid view of the top albumn and song information will open, along with an index of playlists. When clicking upon the playlist options, an embed webplayer will open within the webpage that will then let you start streaming your music.


## Setup/Installation Requirements

* _clone repo to pc_
* _`$ npm install --save-dev`_
* _`$ npm audit fix --force`_
* _go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard) and login to spotify_
* _click create an app and name it Spotify Color_
* _click edit settings and paste http://localhost:8080/ into Redirect URIs_
* _create .env file_
* _write without quotes "CLIENT_ID=" and paste client id from [spotify](https://developer.spotify.com/dashboard) app_
* _`$ npm run build`_
* _`$ npm run start`_

## Known Bugs

* _Not having a profile picture on Spotify account will break part of the website_
* _Not having listened to music on Spotify beforehand, at least for a day or two, will prevent Top 20 and Profile Background to not function correctly_
* _not all genres are listed, so visualizer wont always work. so you have to press visualizer multiple times to work sometimes._
* _if click playlist before top 20, sometimes top 20 will appear out of place._


## License

[GNU](/LICENSE-GNU)

Copyright (c) 2022 Alex Shevlin, Caroline Cerussi, Donovan Weber, Jacob Palaoro, Seung Lee

## Contact Information

* Alex Shevlin <alexshevlin1@gmail.com>
* Caroline Cerussi <caroceru@gmail.com>
* Donovan Weber <donovanweber03@gmail.com>
* Jacob Palaoro <jpalaoro197@gmail.com>
* Seung Lee <shl7@uw.edu>

## Special Thanks 

tobika for the Spotify PKCE example
* <https://github.com/tobika/spotify-auth-PKCE-example>
