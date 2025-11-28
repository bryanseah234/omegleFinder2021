# Omegle IP Finder 2021

A browser-based JavaScript tool to find and geolocate the IP address of your Omegle chat partner.

## Description

This project provides a JavaScript snippet that can be executed in the browser's developer console while using Omegle. It intercepts WebRTC peer connections to extract the IP address of your chat partner and uses the IPGeolocation API to display their approximate geographic location including country, state, city, and coordinates.

## Features

- Intercepts WebRTC ICE candidates to extract IP addresses
- Integrates with ipgeolocation.io API for geolocation data
- Displays location details including country, state, city, district, and lat/long coordinates
- Runs directly in the browser console - no installation required

## Technologies Used

- JavaScript (ES6+)
- WebRTC API
- IPGeolocation.io API

## Installation

No installation required. This is a browser-based script.

1. Get a free API key from [https://ipgeolocation.io/](https://ipgeolocation.io/)
2. Copy the code from `omegle-ipfinder.js`
3. Replace `"your-api-key-here"` with your actual API key on line 3 of the script

## Usage

1. Open [Omegle](https://www.omegle.com/) in your browser
2. Open the browser's Developer Console (F12 or Right-click > Inspect > Console)
3. Paste the modified script (with your API key) into the console and press Enter
4. Start a video chat on Omegle
5. The location information will be displayed in the console when a connection is established

```javascript
// Example output in console:
// ---------------------
// Country: United States
// State: California
// City: Los Angeles
// District: Downtown
// Lat / Long: (34.0522, -118.2437)
// ---------------------
```

## Demo

Use directly on [Omegle](https://www.omegle.com/) by pasting the script in your browser console.

## Disclaimer

1. FOR EDUCATIONAL PURPOSES ONLY
2. USE AT YOUR OWN DISCRETION
3. Respect privacy laws and regulations in your jurisdiction
4. Obtaining others' IP addresses without consent may have legal implications

## License

MIT License

---

**Author:** <a href="https://github.com/bryanseah234">bryanseah234</a>
