# Project 2 - Race Performance
---

### Purpose
This was a school project designed to practice full stack data visualization development. It includes the following:
- Python, NumPy, Pandas, and Jupyter to clean and organize data
- Python Flask–powered API, HTML/CSS,
JavaScript, and PostgreSQL.
- D3.js
- Interative Plotly charts
- A JavaScript library not covered in class (Granim - watch the image on the home screen change colors)
- Two datasets (577,000 rows and 1,900,000 rows each)
- Bootstrap website with multiple pages, dropdown menus, and buttons
- Multiple visualizations

This graphic represents the architecture of the project. 
![Results and Goals](/static/images/tools.png "System Architecture")

### Lessons Learned
I was not able to obtain the data I most desired (race location, school location, and training miles logged) so my charting was limited.  My visualizations here make it seem like training does not affect race performance.  This inspired me to visualize the data by racer instead of by race in a later assignment.

### To View
This website runs off raw data in my SQL database.  The contract I signed to obtain to obtain the data prohibits me from posting the data.  Therefore, this website cannot be viewed.  I have included screen shots of a few Plotly plots. I created a viewable website without raw data on my repository called xc_performance_final.

![Results and Goals](/static/images/plotly_plots.png "Plotly plots")


### Original Assignment Intention

+ This is an interesting topic because many consider training hard as the best way to improve performance. My story will show other factors affecting performance.

+ Factors affecting high school cross country race performance
	-Location (elevation), course (difficulty), heat of location, allergens, goal setting, aggressiveness of goals, home school size, home school location.

### Datasets

+ Two .csv files provided by XC Stats (www.xcstats.com)
	- 577,000 rows of individual race performance statistics since 2011 including a racer id, racer school, racer gender, course id, course distance, previous course time, best course time, if a goal was set/met.
	- 1,900,000 rows of individual training logs including a racer id, date of training, effort value, and feel value.

![Results and Goals](/static/images/dataResultsGoals.png "Results and Goals Data Description")
![Training Logs](/static/images/trainingLogs.png "Training Logs Data Description")

+ Possibly add the following data from outside sources
	- lat/lon of race locations
	- average temperatures (either for cross country season or temperature on race day)
	- allergens in area (average or race day)
	- location of schools (if XC Stats will provide)

### Visualizations

+ Visualizations of factors outside a racer's control
	- bar chart winning race time (y) over years (x) for specific course
	- add male vs female to above chart
	- show school size vs top ten finishes (or school team finishes)
	- show how average temperature (during cross country season) or elevation of home school location (training ground) affects # of top ten finishes

+ Visualizations of factors within a racer's control
	- show how goal setting affects a PR
	- show agressiveness of goal affects a PR
	- show how the porportion of high-effort training days two weeks (consult a coach for predicted ideal time) before a race affects a PR