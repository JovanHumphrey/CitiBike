#CitiBike#

##Project Overview##

###Purpose###
This project was created as part of a business proposal for the city of Des Moines, Iowa. The city is considering starting a bike-sharing program like the one run by CitiBike in New York City. It analyzes data from CitiBike over the month of August. This project addresses the following questions:

•	How does location affect ridership?
•	Who is utilizing the bike-sharing program?
•	What are the peak hours and days of the week for bike-usage?
•	What are the maintenance needs for this service?

[link to dashboard](https://public.tableau.com/app/profile/jovan.humphrey/viz/CitiBike_16490323437220/CitiBikeStory?publish=yes)

##Results##
Using data provided by CitiBike and Tableau’s graphic capabilities, we were able to create seven graphics to tell the story of CitiBike and make the case for a similar program in Des Moines. Below are brief descriptions of each graph.

###Checkout Times of Users###
This graph uses trip duration across the x axis, and number of rides across the y axis. Using an hour filter allows us to see how long riders checkout bikes for.

###Checkout Times by Gender###
Diving further into the previous graph we added a filter for gender. With this filter we can see how long riders of different genders checkout bikes for.

###Number of Rides by Hour###
This graph uses trip stop-times (filtered by days of the week) on the x axis and start-times (filtered by hour) on the y axis. Using Color markers, we can see peak hours across an average week.
Findings: Heaviest bike use occur during morning and evening commute times and is generally higher on the weekends. This indicates that users primarily use the bikes for transportation to and from work and for recreation on their days off.

###Number of Rides by Gender ###
Taking the previous chart as a starting point we added gender groups across the x axis giving us three distinct user categories by gender.
Findings: We can see male users outnumber female users during peak hours.

###Number of Rides by User Type and Gender###
Taking our exploration further we created this chart with genders on the x axis, and user type and day of the week on the y axis. This created a graph with two categories of user type: Customers (general users), and Subscribers. Using Color markers we can see the density of riders by day of the week across user type and gender.
Findings: As before male users outnumber female users, but also subscribers outnumber casual users. This aligns with the idea that most CitiBike users utilize the service for transportation to and from work and as such benefit from the subscription service in a way the less-frequent customers would not.

###Areas of Use###
Utilizing the map function of Tableau, we were able to graph the location of every CitiBike in NYC. Using Color and Size markers we were able to indicate the frequency of use in various parts of the city.
Findings: The most densely populated areas of NYC see the highest number of rides. This indicates that most CitiBike users utilize the service for short distance commutes, between work and home.
###Bike Repair###

CitiBike makes it easy for riders to report problems with the bikes they use. Unfortunately, that only alerts the program to broken bikes. What about maintenance? On the thought that more heavily used bikes will need maintenance more often we created this chart to organize the bikes from most used to least.
##Summary##
By tracking sixteen points of data from CitiBike in NYC during the month of August, investors can imagine how a similar program might work in Des Moines. The data points to users, trip duration, and frequency of use. But I believe the case could still be stronger. Within the limitations of the data provided by CitiBike here are two suggestions for additional graphics.

###Additional Suggested Visualizations###
####Mileage####
With the metrics of start and end locations and trip duration, it may be possible to use this data to determine how many miles riders travel on average. This information can help compare the demand for bikes with availability.
####Rider Age####
Issues of rider-equity span across more areas than just gender. While the data provided doesn't tell us statistical details such as income levels or racial makeup, we can track rider age by utilizing the birthdate information provided in the data. This information can be invaluable when it comes to determining the bike-sharing needs of the community.
