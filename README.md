# WeatherForecast_Android
Reference Solution Video: https://www.youtube.com/watch?v=t_iCYOR0n4c&feature=youtu.be

# Overview
This Android application serves as the mobile counterpart of the project: https://github.com/laidasani/WeatherForecast_Angular_And_Node. Weather Search allows users to search for weather based on current location or any other location entered by the user. Users can know more about the weather through various interactive tabs, showing details like the current day's weather, weekly weather, and photos related to the search query. The user can also mark a city favorite so that it is stored for future ease of access.

# Technologies Used
Node.JS, Android (Java), Volley library, Glide library, XML, JSON, Google Play Services, APIs

# APIs Used
Google Geocoding API, Forecast.io DarkSky API, IP API, Twitter API, Google Custom Search API

# Features
1. The application makes HTTP requests to the Node server which was already created for website using Volley Library.
2. By default, the app opens results from current location which is caught using IP-API.
3. Users can store favorite cities which are accessible at all times even after the app is closed. This is done using Shared Preferences.
4. In case the user want to share the weather they can do this using Twitter button which calls Twitter API and shares the weather details with a custom message, which users can write before sharing.
5. Queried City Images are obtained using Custom Google Search and displayed in a Recycler View.
6. Interactive Graphs and Charts are implemented using MP Android Chart.
7. Splash Screen is implemented before the app loads.
8. Dynamic load symbol covers the screen when data is being fetched.
9. Autocomplete TextView implemented to provide suggestions while searching.
