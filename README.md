# WeatherApp
This weather app is for my Franklin homework but was completed using the Youtube video - https://www.youtube.com/watch?v=PozEoga90r8

QUESTIONS:
i.	Assume that in your API call you received a 401 status code. Which part of your code most probably is not correct? 

401 error indicated an issue with authentication. The authentication used to call the api is added to the url itself, therefore failing to pass it or passing an invalid API Key will throw a 401 error. This is likely a problem with the URL, as thats where the authetication is ultimately passed.


ii.	Explain your design choices and how you used CSS to realize those changes.

The design was kept fairly simple but neat. All content is kept centralized with the name of the application and the temperature being the largest and boldest elements. Added through the Javascript was also the small weather icon specific to the type of weather (clouds for cloudy weather, etc). The css measurement "rem" was used throughout to ensure conistency, as it matches the default font size of the HTML element. In the future, I wish to make it more responsive and modern. 

a.	Submit your heroku link in the github repository read.me file.

https://immense-badlands-37667.herokuapp.com
