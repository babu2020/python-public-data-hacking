Purpose
=======

A follow along for the Learn Python Through Public Data Hacking by David Beazley

http://pyvideo.org/video/1725/learn-python-through-public-data-hacking 

This follow along focuses on the Chicago Transit Authority's (CTA) bus tracker.  The developer website can be found here: http://www.transitchicago.com/developers/bustracker.aspx

However, this follow along focuses on the CTA "Unoffical" API: http://harperreed.github.io/transitapi/ 

Explanation of Files
--------------------

'get_rt22.py' finds buses on route 22 and dumps them into an xml file called 'rt22.xml'

'rt22.xml' is the output from 'get_rt22.py'

'find_north.py' returns all buses north of a specific latitutde and traveling north from 'rt22.xml'

'monitor.py' returns the distance a bus is from a certain latitude in miles