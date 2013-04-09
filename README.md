# Google+ user feed

Get Google+ user posts as an RSS feed

This is my customized version specifically for use with my [If This Then That WordPress autopost recipe](https://ifttt.com/myrecipes/personal/3282469/share), YMMV.

The original is at **http://plusfeed.frosas.net/**

## Installation details

- Get [Node.js](http://nodejs.org/)
- `$ npm install`
- `$ GOOGLE_API_KEY=xxx node app.js` (see [Google API key](https://developers.google.com/+/api/oauth))
- Visit [http://localhost:8080/](http://localhost:8080/)

## MettaCustomizations

- Full-text RSS content using <content:encoded>
- First sentence as title
- Hashtags included at end of title if they are not already in there
- Automatic loading of a default feed if GOOGLE_PROFILE environment variable is present.
