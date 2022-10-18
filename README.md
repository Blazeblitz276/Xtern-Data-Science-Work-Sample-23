# Xtern-WorkSample-Data-Science
Work Sample for 2023 Data Science Internship for Xtern 

#Data Science
***Situation 

In order to make the XTern program the best summer internship program for the participants, the Data Science team is focusing its efforts on helping the XTerns to explore local stores, shops, and destinations. The Data Science team also takes on the challenge to plan a fun day for all the XTerns with tons of activities.  

***Your Task 

- Utilize the open-source map API such as Google Map API, OpenStreetMap, AWS Map API to collect useful data on local stores, shops, and destinations. Clean and organize your data then present it as a table or data frame. Such table or data frame of local stores, shops, and destinations should contain basic information about those locations such as name, address, rating, website, and type. See Example_Data.csv for an example list. 

- Review the data and draw any conclusions you can find from the data set you gathered. Present a one-day (9:00 AM - 9:00 PM) activities plan with time, location name, address, activity type, and duration. See Example_Plan.csv for an example plan. 

- Demonstrate your findings using data visualization tools and well-written explanations. As an important member of the team, you get to come up with your own analysis and explain it! So try your best to dig out any useful information from this data set. Sky is the limit! 🤓 

***Final plan

- Assuming we already had breakfast starting from IUPUI Campus at 9 AM to move to Zoo with estimated travel time of 5.521667 minutes.
- Morning Visit (Zoo)- Indianapolis zoo at 9:20 AM - 1:30 PM before moving for lunch with estimated travel time of 6.240000 minutes. 
- Lunch (Italian restaurant) - The Old Spaghetti Factory at 1:50 PM to 3:00 PM then moving out for desert with estimated travel time of 8.910000 minutes. 
- Desert (Ice Cream Store) - Sub Zero Nitrogen Ice Cream from 3:20 PM to 4:00 PM then travelling to Museum with estimated travel time of 8.910000	minutes.
- Evening Visit (Museum) - The Children's Museum of Indianapolis spending 3.5 hours here from 4:20 PM to 7:50 PM then moving out for dinner with estimated travel time of 7.230000 minutes.
- Dinner (Indian restaurant) - Chapati spending an 50 min to an hour here we can complete the trip till 8: 50 PM and return to IUPUI Campus with estimated travel time of 5.305000000000001 minutes.

***Output Files

- Data.xlsx
- Plan.xlsx

*** To repeat any of the results

- Please run all the cell at once and provide input related to the 4 user preference questions
- Post the answering the entire code will run cutomatically and provide the results in the above mentioned files

*** Strong points

- The allows user choice of locations by roviding general queries to select from
- It also calculates the choices for the next activity by updating the viscinity after each activity 
- The code is readable and modular(for major API call). 
- It utilizes the google API for getting location and details for places and used openstreet map visualization using folium

*** Drawbacks

- Code is bulky and needs optimization and further modularization
- Needs dynamic optimization for location selection instead of highest footfall method
- Needs update to user preference fucntion to allow more activities and automatic time plan evaluation

*** Note

- The API key is removed from the API key file to avoid misuse. Please inform me via any means of communication for the same if required.


