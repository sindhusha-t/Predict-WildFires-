# Predict WildFires 

### Cloud Computing project:              
**Professor: Choi, Baek-Yound**

### Team Members:
Sindhusha Tiyyagura    
Pradeepika Kolluru

### Main Objective:
We will be using NASA fire information and predict the wildfire alert range for the particular region and also show required comparisons across the regions along with the MAP User Interface.       

### Requirements and Design:
1) Gather the data from the NASA FIRMS API:             
       a) NASA provides various data publicly - that is from climate and weather to solar flares and wildfires.         
       b) FIRMS API provides data for each `region` and In each region it provides the `brightness` of fire for each `latitude` and `longitude` locations.           
       c) It provides real time active data for last 24 hours, 48 hours, 72 hours and 7 days.           
       d) It provides data for past month, year as well, but it takes more time to retrieve the data.          

2) Create a basic model ( using existing Machine Learning technique `Linear Regression` ) for training the data to the model.           
       a)  Will be using Simple Linear Regression model as there is only one input variable `brightness` sufficient for predicting the range of the wildfire.                 
       b) Linear Regression establishes a relationship between the output variable and the input variable by fitting in a single line.              
       c) During the training process, will be cleaning the data to remove the outliers from the training data.            
       d) Final Target variable will be given in the range of either 0 to 1 or 0 to 10.                   

3) Web User Interface for the client.                
       a) Showing world map where users can point to a specific location ( determines latitude and longitude ) to get the wildfire range at that location for last 24, 48, 72 hours and 7 days. If possible it can be shown for past 1 month data as well.                 
       b) Showing a bar graph comparing wildfire for different regions selected by the user.                  
       c) Showing the time graph( line graph ) comparing the changes in the wildfires across time period for a particular region selected by the user.                   

4) Deploying the web page to the Cloud server.                

### Technologies:                
Angular 7 for creating the web pages.             

### Sample NASA FIRMS API Data:              
for last 24 hours:              
![](https://github.com/sindhusha-t/Predict-WildFires-/raw/master/Documentation/Screenshots/NASA%20sample%20data.PNG)

### Use Case Diagram:
![](https://github.com/sindhusha-t/Predict-WildFires-/raw/master/Documentation/Screenshots/Use_case_diagram.png)

### Links:
[NASA FIRMS API](https://firms.modaps.eosdis.nasa.gov/web-services/)
