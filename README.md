# City Weather (Open‑Meteo)

## Overview
Simple, single‑page web app to fetch and display current temperature and humidity for any city using the Open‑Meteo public API. No API key required. Styled with Bootstrap 5.

## Setup
- Download or clone the repository.
- Open index.html in any modern web browser (Chrome, Firefox, Edge, Safari).
- Internet connection is required to reach the Open‑Meteo APIs and Bootstrap CDN.

## Usage
- Type a city name (e.g., London, Tokyo, San Francisco).
- Click “Get Weather” or press Enter.
- The app geocodes the city and shows current temperature and humidity for the best match.

APIs used:
- Geocoding: https://geocoding-api.open-meteo.com/v1/search
- Weather: https://api.open-meteo.com/v1/forecast with current=temperature_2m,relative_humidity_2m

## License
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.