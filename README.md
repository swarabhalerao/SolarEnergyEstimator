# SolarEnergyEstimator
Our first ever hackathon submission. 

## About
A solar energy calculator that tells you the amount of solar energy you can harvest from your rooftop and how much you can earn from the surplus.\
**Built in:** Python

## Working
Input the location in the interface. Here you can choose your current location or select any other location from a dropdown.
Then, enter the amount of area you wish to apply solar panels to.

On clicking `Enter`, it gives you a pop-up containing full details regarding **total energy produced**, remaining **surplus** after average household consumption and **profit earned** from it.

## Challenges Faced
Webscraping for personalising the results using IP address and location and then looking up the statistics about the location from online aggregators while keeping API requests minimum were the biggest hurdles and took a lot of time. We tried multiple API but either the data was severly outdated or it had a limit to API requests.\
On the GUI front, the pop up windows took a lot of attempts to get right given the fact that we are new to Tkinter and have no idea what the syntax is supposed to be.

## Results
We ended up using a website that changes URL according to the location and scoured the .json file to filter out the relevant data.\
We learnt up the ins and outs of Tkinter in a night and managed to make our display as needed.
