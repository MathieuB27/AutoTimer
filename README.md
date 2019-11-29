Tracking the desktop applications in real time and time spent on each application.

Check out this for more https://youtu.be/ZBLYcvPl1MA 

Dependencies:

- selenium


Windows Depencies

- pywin32
- python-dateutil
- uiautomation 


activities.html will you you the resume of the json file of the day.
If you need to check a different day pass the date in the url like so :
resume.html?date=2019-11-29

To start a small web server go in your app folder and run this command :
python -m SimpleHTTPServer

And go to this address
http://localhost:8000/activities.html

Or this address for the data from the 2019-11-29
http://localhost:8000/activities.html?date=2019-11-29
