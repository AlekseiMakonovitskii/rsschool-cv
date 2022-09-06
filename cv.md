# Aleksei Makonovitskii
## My contact info:
* Phone: +79006051261
* Email: alexmakondev@gmail.com
* Telegram: @alexqvod
* GitHub: https://github.com/AlekseiMakonovitskii
* CodeWars: https://www.codewars.com/users/AlekseiMakonovitskii

## About me:
Hi, I have been studying front-end development for 5 months,
Before that, I already had experience in external EPAM courses.
I want to get better and better at front end development, learning new technologies. 
My goal is to work in a good Company with good people.

## Skills:
* HTML
* CSS
* SASS (started)
* JavaScirpt 
* React (started)

## Code example:
```
const getCityName = (lat, lon, apiId) => {
  const url = `https://api.openweathermap.org/geo/1.0/reverse?lat=${lat}&lon=${lon}&limit=1&appid=${apiId}`;
  fetch(url)
    .then(res => res.json())
    .then(city => getCityCoords(`` + city[0].name));
};
```

