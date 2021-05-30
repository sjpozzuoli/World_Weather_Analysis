# World Weather Analysis

### The purpose of this analysis is to use API calls to gather the current weather for a random set of latitudes and longitudes. Once that analysis is generated, Google maps will be utilized to map driving directions of a possible vacation by choosing 4 different cities within the USA.

## Results

#### After generating the random latitudes and longitudes, the results were entered into a dataframe so they could be analyzed further. The below dataframe shows the fields that were captured in an attempt to add information via the Google API.

![Weather_DF](https://user-images.githubusercontent.com/81929616/120115200-98cc4380-c150-11eb-9f91-efd5963279cc.png)

#### Once this dataframe was compiled, the Google API was able to be utilized. The first part of the excercise was to add markers that included the weather data in that specific city. This would give the user an idea of the area of the world that they would like to travel to. This information is very useful to help the user decide what type of vacation they are looking for. 

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/81929616/120115311-30319680-c151-11eb-8cc5-5583a4d53466.png)

#### The above shows a few examples of what information is included. 

#### Once the country and cities of the desination are chosen, the search was narrowed down to only include the chosen cities. 

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/81929616/120115381-6a029d00-c151-11eb-8216-6d7fe62c994f.png)

#### The final step is to create a driving directions map to show the route that the user would have to take in order to visit all of the chosen cites and then return to their home. Using the same cities as in the screen shot above, the driving directions were generated and mapped for the user. 

![WeatherPy_travel_route](https://user-images.githubusercontent.com/81929616/120115436-a1714980-c151-11eb-8fd9-c992d9f67cd5.png)
