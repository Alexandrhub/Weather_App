# Weather_App
A simple python backend Jetbrains Academy Project

### :partly_sunny: Weather App made on Flask and SQLite by [JetBrains Academy's Python Developer course](https://hyperskill.org/tracks/29)

![screen](https://user-images.githubusercontent.com/51692800/114059212-91ee2680-98ad-11eb-9950-f0263751285f.png)

## :zap: With this app you can:
1. Get current weather in any city of the world (city will automatically added to database)

  App takes existing city name as an input and generates a card of a given city with:

  • temperature
  
  • colloqual description of the temperature
  
  • background image which correlates to local time of the city
  
2. Delete city from database
Everytime you refresh the page or add/delete a card, data of every saved card will also be updated 

for more info on OpenWeatherAPI, visit: 
https://openweathermap.org/current

## :umbrella: Installation and dependencies
```sh
git clone https://github.com/Alexandrhub/Weather_App.git
cd Weather_App
pip install -r requirements.txt
```

## :star2: Run
```sh
cd web
python app.py
```
or just (if Python is added to your PATH)
```sh
cd web
app.py
```
App also uses data from OpenWeatherApi, which is essential to run the app,
so in order to get a valid API key,
you must register at https://home.openweathermap.org/users/sign_up


Once you get your API key, assign your API key to API_KEY variable in app.py file

### 
The command takes two arguments host address and port, you don't have to specify these and by default the app will be run on
localhost port 5000  --->  http://127.0.0.1:5000/
