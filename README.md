# gulp_boilerplate
Quick, basic gulp boilerplate with browserify, sass compiling, and express server.

##Setup and usage:
1. Make sure you have Node installed.  You can check in the terminal by typing `node -v`
2. Navigate to the gulp_boilerplate project folder.  If you saved it to your desktop `cd ~/Desktop/gulp_boilerplate` should get you there.
3. Type `npm install`.  This will install all required node modules.
4. Open a second terminal window and navigate to the project folder there as well.
5. In the first terminal window type `npm start`.  This will start a server listening on localhost:3000.
6. In the second terminal window type `npm run watch`.  This will start a watch which will compile your scss to css and bundle your JS files.  This will happen everytime you update and save your scss files in `public/css` or your js files in `public/js`.
7. Open `localhost:3000` in your browser of choice and begin developing!

##Other commands
* `npm run minify` will minify your files and images.
* `npm run build` will build your files without watching for any changes.
* `npm run postinstall` will both build and minify your files.  This also helps when deploying to something like Heroku as it will run `npm install`, `npm postinstall`, and then `npm start`.
