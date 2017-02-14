# Mini-Flickr
A waterfall Flickr-like gallery using BEAN stack (Bootstrap, Express, AngularJS, NodeJS)

How to install this project

Run following command in your terminal:

git clone https://github.com/logydoghan/mini-flickr.git
cd mini-flickr
npm install ( if npm is not installed, install Node.js)
bower install ( if bower is not installed, run "npm install -g bower")
angular-deckgrid install(using bower install angular-deckgrid; choose lazyload)
Apply a Flickr api key at https://www.flickr.com/services/api/misc.api_keys.html
Put your Flickr api key in file service/flickrService.js
node server.js
Now you should be able to access the project by going to http://localhost:3000 in your browser.
