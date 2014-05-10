#Purpose

A follow along for the [Learn Python Through Public Data Hacking] (http://pyvideo.org/video/1725/learn-python-through-public-data-hacking) by [David Beazley] (http://www.dabeaz.com/).  The workshop focused on two specific data sets: the first dealing with the CTA Bus Tracker and the second dealing with City of Chicago Data Portal

##CTA Bus Tracker (Folder:cta)

This portion of the workshop focused on the Chicago Transit Authority's (CTA) Bus Tracker.  The developer website can be found [here] (http://www.transitchicago.com/developers/bustracker.aspx).  However, David focused on the [CTA "Unoffical" API] (http://harperreed.github.io/transitapi/).

###Explanation of Files

'get_rt22.py' finds buses on route 22 and dumps them into an xml file called 'rt22.xml'

'rt22.xml' is the output from 'get_rt22.py'

'find_north.py' returns all buses north of a specific latitude and traveling north from 'rt22.xml'

'monitor.py' returns the distance a bus is from a certain latitude in miles


##City of Chicago Data Portal: Potholes Reported (Folder:potholes)

This portion of the workshop focused on the City of Chicago Data Portal, specifically [potholes reported using the 311 service request system] (https://data.cityofchicago.org/Service-Requests/311-Service-Requests-Pot-Holes-Reported/7as2-ds3y).

###Explanation of files
