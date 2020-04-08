# About the Project

This project is part of a exercise for the FEND Udacity Nanodegree program. It implements a Travel App which produces a weather forecast from [DarkSky API](https://darksky.net/). Enter Location name and Date and you will get back the weather forecast and a picture of the destination from [Pixabay](https://pixabay.com/).

## Getting started

1. Fork this repo and clone it down to your machine. Alternatively you may download the zip folder and unzip it. Open in in an IDE (VS code is suggested)

`cd` into your new folder and run:

2. `npm install` thus you will have all your node-modules installed.

To make all this API's work, you need to get your own API Keys. (username for Geonames)

3. Signup for an API keys

Get your Keys form the following services:

- [Geonames](https://www.geonames.org/) to get LAT/LON coordinates for your location
- [Dark Sky](https://darksky.net/) to get the Weather forecast (based on LAT/LON)
- [Pixabay](https://pixabay.com/) to get a nice picture (url is provided)

Signing up will get you an API key.

4. Hide your Key using a .env file

- [ ] Create a new `.env` file in the root of your project
- [ ] Fill in the API user name and keys in it and save it all

```
USER_GEO=**************************
KEY_DARK=**************************
KEY_PIXA=**************************
```

- [ ] Go to your .gitignore file and add `.env` - to make sure we don't push our environment variables to Github! to protect API keys.

5. Dependencies

- Dependencies and Development Dependencies are listed in package.json file. npm install mentioned at step 2 installs all the dependencies.
