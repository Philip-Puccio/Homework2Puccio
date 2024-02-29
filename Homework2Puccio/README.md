# Homework 2
 So far my prototype is in its very early stages. the first page is a basic welcome page with a forecast I made up, and emojis using css that matches the description. I then have a bootstrap class that uses the anchor to navigate to my second page, where I created a table for the 7 day actual vs forecast data that I made up. I used some custom CSS text for both the header and the <h2> under the table, and they differ slightly in color because I arbitrarilly wanted them to be different. I asked chatGPT to create a javascript button that changes the emoji on the first page as well, and it made a button that randomly selects emojis from an array of potential options using the MATH class and MATH.random to make a pseudorandom number to pull from.
 
Here were my research summaries: 

Website Analysis

The first website I chose to look at was [weather.com](weather.com). This is so I could take a look at their 10 day forecast, as while I am not directly using this same function, I am working with using the data it shows in my prototype. I noticed that one of the most notable instances of interaction the page gives you is a little dropdown menu that gives you more details about that day’s forecast. It starts as just the temperature, and when the menu is opened, it gives you various data points such as sunrise and sunset, humidity, wind speeds, and UV. Those four previously mentioned datapoints are also set up in a table, not unlike the one we made for taco.html in class. Something I could look into that they incorporate as well could be icons based off of the general weather pattern (IE cloudy, sunny, rain, high winds)

The second website I looked at was [accuweather.com](accuweather.com). Once again, I specifically looked into the 10 day forecast page, as that is what my prototype looks into mostly. It is less interactive than the weather.com one, as it had no dropdown menus to interact with, instead having a new page for each specific day. Once on this page, it would display the usual forecast data, a little info about the wind that day, then a radar map of the area. In the url for each specific day of the forecast they have an = n, where n is how many days out we are from that specific day, so I imagine that is how they can quickly change the data for that specific day.

The final website I investigated was [forecast.weather.gov](forecast.weather.gov). This was significantly less interactive than the  other websites, as it was just written out in regular text with no icons, more info on a separate page, and less data in general. They are mostly just descriptions of what to expect, without much data to back it up, where the other pages had useful data to back up their predictions and forecasts. Definetely the most basic between the websites. 

Repository Analysis
I looked at a respository called [weatherbench 2]([forecast.weather.gov](https://github.com/google-research/weatherbench2)). This is a self described, data driven weather forecasting. Their readme directed me to their website, where the opensource code was available, as well as advanced data that the system uses. It goes into probability and statistics that they use to predict weather patterns.

The second repository I found was the [WeatherVista interactive weather app]([[forecast.weather.gov](https://github.com/google-research/weatherbench2)](https://github.com/wasimtikki120/WeatherVista-Interactive-Weather-App)). The readme was very in depth showcasing screenshots and descriptions of what the app looks to accomplish. From what I gather it is basically an accurate forecast of upcoming weather very much formatted like one of the websites I have visited and wrote about. They are particularly emphasizing their search implementation as well as their custom icons depending on the time and weather of the area you search for, as well as the UI strides they worked for. It seems like a very good alternative to a weather website if a person had a desire for such a thing. 

I would like to actually pull real data for the table as well as make everything look nicer and more complete. I would also like to expand on data for different forecasting sites for different places, maybe include a searchbar so you can look up the accuracy for forecasts in your specific area.

The websites I used to help me with this were [weather.com](weather.com), [accuweather.com](accuweather.com), [forecast.weather.gov](forecast.weather.gov), [weatherbench 2]([forecast.weather.gov](https://github.com/google-research/weatherbench2)), [WeatherVista interactive weather app]([[forecast.weather.gov](https://github.com/google-research/weatherbench2)](https://github.com/wasimtikki120/WeatherVista-Interactive-Weather-App)), [Chat GPT](https://chat.openai.com), and [W3 Schools](https://www.w3schools.com)

I used AI to help me mostly remember how to implement certain things, for example, I used the prompt: Make a table in html that is 3 columns wide and 7 rows tall. I edited it later to put in data I wanted, as well as changed the size it took up on the webpage and the amount of columns, but I also used AI to help write parts I wasn't too familiar with, asking Can you make a button using javascript that turns the emojis from this code into a different emoji

<h1>Today's Weather In Your Area: </h1>
<h2>
    56 Degrees and Sunny <p style="font-size:48px">
        &#127774; &#x1F31E; &#127774;
    </p>
</h2> 

I also asked Can you turn this code into a button using a bootstrap class? 
<a href="/SearchResults">7 Day Forecast Ranking</a>
To turn the code into a button as shown in the page.

Finally, I asked: how to make a hyperlink in markdown because I was lazy about 10 minutes ago.

All of the AI worked well and helped me learn by seeing an example. For the most part I tried to change the code it gave me as to not feel too badly, but I feel like giving it code to improve such as my use of bootstrap classes and javascript implementation made me beleive that I wasn't making it do all the work. I feel like it is a very good tool for learning by example and helping me implement my ideas better when I am blanking or finding something hard to turn my idea into functioning code.
