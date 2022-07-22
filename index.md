![Headstone Image](https://raw.githubusercontent.com/BlueStampEng/BSE_Template_Portfolio/de8633f62b5da2234992a0178a6a72fd6df7e7e1/branding/BlueStamp-Logo.svg)

# Eli's Smart Mirror
A mirror that utilizes a monitor to display compliments, the weather, calendar, and the time.

| **Engineer** | **School** | **Career** | **Grade** |
|:--:|:--:|:--:|:--:|
|Elijah A |Benjamin Banneker Acadmey | Civil Engineering | Incoming Senior

![Headstone Image](https://github.com/Ebandzz/Smart-Mirror/blob/dfb73978e4207027f9f0e45c256ff9ea2c3bd870/MMss.png)

 


# Third Milestone 😃
In summary, I downlaoded rasperrypi onto my computer. Then, I connected my raspberry pi to my monitor. After, I created a SSH file so I can download Magic Mirror. Then, I installed Magic Mirror onto my VS appplication. Once the base was completed, I made a few customizations to my project such ass adding compliments, adding the weather forecast, and changing the colors for the calendar, weather icons, and some of the text.

<iframe width="650" height="365" src="https://www.youtube.com/embed/mhA53ow2ehU" title="Eli A Milestone 3" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
 
# Second Milestone 😄
My second Milestone was customizing Magic Mirror. First, I added effects for my alerts. Then, I decided to change the color for my calendar. After, I  added compliments to my project. The compliments I added were based on the date, time, and weather. For instance, when it's morning, my mirror will greet me with a good morning message. Additonally, when it's raining, my mirror will message be to be safe during rainy weather. I added the weather forescast in order for my weather compliments to work. When adding the weather, I added my location and changed the weather from celsius to fahrenheit. Also, I added colors for weather icons and changed the color to a light color purple in the main css.file

<iframe width="650" height="365" src="https://www.youtube.com/embed/MqkOFSvBFJ4" title="Eli A Milestone 2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# First Milestone 😁
My first milestone was setting up the base for my project. First, I set up my raspberry pi and connected it to my monitor. Then, I pinged my IP address. After, I got a coding apllication called Visual Studio to create a SSH file for my project. Lastly, I installed Magic Mirror, which is a Node JS Application. Magic Mirror assisted in generating the base I need for my project. With it, I can chan ge or add codes to make my smart mirror suitable for me.

  <iframe width="650" height="365" src="https://www.youtube.com/embed/HZR-vvzeD9Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

 # Preview of setup
 Weather compliments

					showers: ["Not bad"],
					thunderstorm: ["AHHHH RUN"],
					 snow: ["snow in NY?"],
					showers: ["Not bad"]
					fog: ["Don't be lacking"],
					rain: [
						"Stay dry!"
					],
                                         night_clear: [
						"Enjoy the night",
					],
					night_cloudy: [
					" It's peaceful out"
					],
					night_showers: ["be chill tonight"],
					night_rain: ["rainy nights are the best"],
					
     
   Weather Configuration 
 	                
			
			config: {
				weatherProvider: "openweathermap",
				type: "current",
				location: "New York",
				locationID: "5110302", //ID from http://bulk.openweathermap.org/sample/city.list.json.gz; unzip the gz file and find your city
				apiKey: "0d3f272a11a8f28806cc6914217d3798",
				units: "imperial",
				roundTemp: true,
				degreeLabel: false,
				showPeriod: false,
				showPeriodUpper: false,
				roundTemp: true,
				timeFormat: 12,
				
				
  Setup for Weather icons
        	

              .wi-day-cloudy {
              color:burlywood;
                      }

                .wi-cloudy{
             color: #ffffff;
                           }
                .wi-rain{
               color: #0000ff;

                           }

                 .wi-day-rain{
              color:aquamarine;
                             }
              .wi-day-showers{
            color:cornflowerblue;
                               }
          .wi-day-sunny-overcast{
             color: gold;
                               }

                .wi-night-clear{
                   color: grey;
                               }
