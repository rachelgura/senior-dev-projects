As part of the Senior Web Developer a meet-up event planner has to be built by leveraging high conversion web forms, as well as web tooling & automation.

Meet up event planner is a web app for creating events with features as:

HTML5 geolocation
Foursquare API
Responsive design

Install

After cloning the repository you should run:

npm install

bower install

Being inside of the directory of the project you can run:

serve

For the development phase, use the command gulp serve to lunch server which supports live reload of your modifications.

test

For testing, a fully working test environment is shipped. It uses Karma (with gulp test) for the unit tests.

build

For production, use the command gulp or gulp build to optimize the files for production, they will be saved optimized in the dist directory.