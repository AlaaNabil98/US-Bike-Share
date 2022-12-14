# US-Bike-Share
![Cover Image](https://camo.githubusercontent.com/b7735976ee3862a2bc5d191887c8346b60470c0f754a48647008963ce49acb71/68747470733a2f2f766964656f2e756461636974792d646174612e636f6d2f746f706865722f323031382f4d617263682f35616137373138645f64697676792f64697676792e6a7067)
# Project Overview: Overview
In this project, I made use of Python to explore data related to bike share systems for three major cities in the United States - Chicago, New York City, and Washington. I have written code to import the data and answer interesting questions about it by computing descriptive statistics. I have also written a script that takes in raw input to create an interactive experience in the terminal to present these statistics.


## What Software Do I Need?
To complete this project, the following software requirements apply:
* You should have Python 3, NumPy, and pandas installed using Anaconda
* A text editor, like [Sublime](https://www.sublimetext.com/) or [Atom](https://atom.io/).
* A terminal application (Terminal on Mac and Linux or Cygwin on Windows).

# Project Details: Bike Share Data
Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.

Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

In this project, I will use data provided by [Motivate](https://www.motivateco.com/), a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. I will compare the system usage between three large cities: Chicago, New York City, and Washington, DC.

## The Datasets
* Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:
    * Start Time (e.g., 2017-01-01 00:07:57)
    * End Time (e.g., 2017-01-01 00:20:53)
    * Trip Duration (in seconds - e.g., 776)
    * Start Station (e.g., Broadway & Barry Ave)
    * End Station (e.g., Sedgwick St & North Ave)
    * User Type (Subscriber or Customer)
* The Chicago and New York City files also have the following two columns:
    * Gender
    * Birth Year
* The original files are much larger and messier, and you don't need to download them, but they can be accessed here if you'd like to see them ([Chicago](https://www.divvybikes.com/system-data), [New York City](https://www.citibikenyc.com/system-data), [Washington](https://www.capitalbikeshare.com/system-data)). These files had more columns and they differed in format in many cases. Some [data wrangling](https://en.wikipedia.org/wiki/Data_wrangling) has been performed to condense these files to the above core six columns.

## Statistics Computed
I learned about bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics. In this project, I have written code to provide the following information:
* Popular times of travel (i.e., occurs most often in the start time)
    * most common month
    * most common day of week
    * most common hour of day
* Popular stations and trip
    * most common start station
    * most common end station
    * most common trip from start to end (i.e., most frequent combination of start station and end station)
* Trip duration
    * total travel time
    * average travel time
* User info
    * counts of each user type
    * counts of each gender (only available for NYC and Chicago)
    * earliest, most recent, most common year of birth (only available for NYC and Chicago)
