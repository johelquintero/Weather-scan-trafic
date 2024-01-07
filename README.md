## Running locally:
1. Download & Install [node.js LTS](https://nodejs.org/en/)
2. Get weather.com, developer.tomtom.com and mapbox.com API keys.
3. Navigate to `/webroot/js` and open `config.js`.
4. Find the line with `var api_key = 'YOUR_API_KEY'`. Replace YOUR_API_KEY with the weather.com API key.
5. Find the line with `var map_key = 'YOUR_API_KEY'`. Replace YOUR_API_KEY with the mapbox.com API key.
6. Find the line with `var traf_key = 'YOUR_API_KEY'`. Replace YOUR_API_KEY with the tomtom.com API key.
7. In terminal, run `npm install --production` in the root folder of this project. This will install any dependencies.
8. In terminal, run `npm start` in the root folder of this project. This will start a local web server.
9. Follow the link in the console output.

##Steps for getting tomtom.com traffic API key:
1. Go to developer.tomtom.com
2. Click "Login" at top right of screen.
3. Click "Create an Account" if you do not have a login, or just sign in if you do have an account.
4. Go to your dashboard by clicking you user profile if you are not already sent to the dashboard, and clikc "API & SDK Keys" at the left menu.
5. Click "Create Key"
6. Copy your key.
