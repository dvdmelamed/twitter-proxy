# twitter-proxy

Tiny Twitter API proxy server. Allows you to make requests to the Twitter API from the comfort of your browser.

## Getting started

- Create an app on https://dev.twitter.com – the URLs and name don't matter, you won't be using it to authenticate people
- Update `config.js` with the "Consumer key" and "Consumer secret"
- Generate yourself an access token and access token secret for the app and add this to `config.js`
- Run the app: `node server.js`

You can now make requests to Twitter API URLs, but to `http://localhost:7890`, from your browser.

## License

[MIT License](http://phuu.mit-license.org/)