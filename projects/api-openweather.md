---
layout: post
tags: [API, Postman]
---

In this is API request I've got useful information about the weather. I've used the site [OpenWeather][openweather-link] to get the current weather data of the San Salvador/El Salvador city. This data include a lot of information, for example:

| The name of the city | San Salvador |
| The tempeture | 23.96º (Celsius) |
| Weather | Clouds |

This is how the request looks like from the API platform:
![API platform](/images/projects//openweather.png)

And this is the complete response of the API:
```json
{
    "coord": {
        "lon": -89.1914,
        "lat": 13.699
    },
    "weather": [
        {
            "id": 802,
            "main": "Clouds",
            "description": "scattered clouds",
            "icon": "03n"
        }
    ],
    "base": "stations",
    "main": {
        "temp": 23.96,
        "feels_like": 23.95,
        "temp_min": 23.96,
        "temp_max": 23.96,
        "pressure": 1013,
        "humidity": 59,
        "sea_level": 1013,
        "grnd_level": 939
    },
    "visibility": 10000,
    "wind": {
        "speed": 2.71,
        "deg": 337,
        "gust": 6.45
    },
    "clouds": {
        "all": 25
    },
    "dt": 1703031825,
    "sys": {
        "type": 1,
        "id": 7222,
        "country": "SV",
        "sunrise": 1702988057,
        "sunset": 1703028798
    },
    "timezone": -21600,
    "id": 3583361,
    "name": "San Salvador",
    "cod": 200
}
````


**Tech stack:** API, Postman 

[openweather-link]: https://openweathermap.org/
