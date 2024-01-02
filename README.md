## Running locally:
1. Download & Install [node.js LTS](https://nodejs.org/en/)
2. Get weather.com, tomtom.com and mapbox.com API keys.
3. Navigate to `/webroot/js` and open `config.js`.
4. Find the line with `var api_key = 'YOUR_API_KEY'`. Replace YOUR_API_KEY with the weather.com API key.
5. Find the line with `var map_key = 'YOUR_API_KEY'`. Replace YOUR_API_KEY with the mapbox.com API key.
6. Find the line with `var traf_key = 'YOUR_API_KEY'`. Replace YOUR_API_KEY with the tomtom.com API key.
7. In terminal, run `npm install --production` in the root folder of this project. This will install any dependencies.
8. In terminal, run `npm start` in the root folder of this project. This will start a local web server.
9. Follow the link in the console output.
