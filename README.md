# Question-App
User and Technical Guide
This is a browser-based App that will allow the system to do the following:
  Create a new question by clicking on a point on a Leaflet Map and adding the quesiton and four possible anwers. The answer wil be stored in a database on the webserver.
  
  This app consists of three parts, main map for selecting question points, a tracking map and a question form. Usuful functions are added. These are described below.
  
  1. Main map
    The map on the top is a clickable map showing you a clicked coordinate. The pop up will be come up when clicking on a point on a Leaflet map and the coordinates in the pop up are automatically inserted into the form when clicking the coordinates.
    The button under the this map is to allow to zoom in to user's current position. When the button is toggled off, the map is set as default. 
    
  2. Tracking map
    The small map below a question form is tracking user's positioin with a pink marker. The pop up will be shown only when clicking the marker and the coordinates does not inserted into the form when it is clicked.
    
  3. Question Form
    This form is for creating questions of Quiz App. Each enrty must be filled in and if there is non-sense input, the upload will not be carried out.If the upload button is pushed, the data in the form will be sent to a database and "Upload Has Completed" message will be displayed.
   
  
![2018-05-09 02 34 44 1](https://user-images.githubusercontent.com/35526637/39791530-0fac2238-5334-11e8-934a-2e52acad99c1.png)
