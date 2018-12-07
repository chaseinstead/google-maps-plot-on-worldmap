# google maps location history plotter
creates a path out of collected google maps location history and shows you what google knows about you.

# installation 
```
pip install -r requirements.txt
```
the plotter needs a .json file with location data that google maps collects - most likely [whether you want it or not](https://www.independent.co.uk/news/world/americas/google-location-data-privacy-android-sundar-pichai-a8490636.html). you can [download your own location history here](https://takeout.google.com/settings/takeout) and save it in the same folder as "location_history_plotter.ipynb". 

# to do
- increase readability: the code is still chaotic (esp. intertwining of functions)
- adjust the points' colors depending on altitude of location point (works, but coloring has to be improved)
- automate getting rid of outliers
- automate map size (take southernmost, northernmost, easternmost and westernmost points and calculate map accordingly)
- add more statistics, e.g. longest distance travelled within 24 hours
- find out the country of each location point and plot high and low points or places of longer stay, etc.
