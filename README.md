# python-api-challenge
Module 6 homework

WeatherPy
For both sections of this homework, I was able to refer to a few of the Mod 6 in class exercises. This was extremely helpful in remembering the "random" function being in numpy, and redoing the "if city NOT IN cities" routine to get the list of UNIQUE values.

In requirement 1 I got stuck with the url for the API call.  I used BCS Assistant, and Diego helped me a lot. He helped me rewrite the endpoint url from a to b:
    #city_url = f"{url}q={city}&appid={weather_api_key}"     ---this was my effort. Working version below.

    city_url = "http://api.openweathermap.org/data/2.5/weather?units=Metric&APPID=" + weather_api_key + "&q=" + city

The rest of the exercise was good, making us parse through data and do the plotting. Of course, my first effort was making it harder than it had to be, but I got it eventually.

I then noticed my api keys in the config file were still showing in github. Turns out I had 2 gitignore files and two config files, due to some mistakes made setting up the repo. Again I had to call BCS to help me find what was where and fix it.  Can't remember the person's name.

Finally, requirement 2, making a function to plot.  I tried, and couldn't figure out how to do it, what had to be passed in and how, etc.  I finished the assignment doing each plot without a function, UNTIL I was back on BCS for a different issue later.  Robert L helped me build the function, and showed me how each variable works, including annotation coordinates.  I then went through each plot again and recreated them using the function code.


VacationPy

I found VacationPy to be fairly straightforward, due to the fact I could use class exercises, especially 3.7 from Mod 6, Restaurant exercise, to get refresher on how most of that works, with creating the parameters, and lat and lng and doing the API call, converting to JSON and pulling out other fields, in this case hotel name.  I did have an issue with geoviews, it was not working, even though I did do an install, it was on conda prompt, so it was not being seen by my repo. Once again BCS to the rescue.






