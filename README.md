#Weather app using Vanilla JavaScript

Reference: https://www.geeksforgeeks.org/weather-app-using-vanilla-javascript/?ref=gcse

Step 1: Now go to https://openweathermap.org/ and create an account and get your API KEY.
Step 2: After that, you can create a folder and add a file, for example, index.html and script.js file.
Step 3: We can fetch geographical coordinates using the following approaches:

Calling API by geographical coordinates- latitude and longitude
  api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={API key}

Calling API by city ID
  api.openweathermap.org/data/2.5/weather?id={city id}&appid={API key}
