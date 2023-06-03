# RedEye
========

This project focuses on analyzing the RedEye service, an off-campus safety escort service for Northeastern students. Our aim is to evaluate the accessibility of the RedEye service and the safety of the surrounding neighborhoods. By gathering insights from the dataset, we will provide suggestions for improving the RedEye service and explore alternative commuting options. Ultimately, our goal is to assess whether the RedEye service ensures sufficient safety for the majority of Northeastern student commutes.
----
Data source
==
1. Student Survey :
* First hand collection of data (~80% graduate and 20% undergraduate)
* Understand more about the RedEye service itself
* Understanding pattern of students leaving campus during RedEye service hours.
2.Boston's Crime incident Report(Public source):
* Secondary source to supplement our current data set. 
* Analyze the neighborhood which majority of students lives are covered by Red Eye service commute areas(2 miles)
* Crimes from the start of 2022 - now, used to check safety of students during their commute to campus.
3. MBTA:
* Chosen as a comparison for alternate commute to RedEye service.
* Understand reliance and communication of MBTA services.
* Public source

Method and Tools
==
* Cleaned and wrangled the datasets (crime data,student survey,MBTA ) using excel and Python.
* Libraries used : Numpy, Pandas, GeoPandas, geopy.distance, sklearn.neighbors, uszipcode.
