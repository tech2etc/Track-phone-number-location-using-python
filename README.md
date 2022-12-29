# Track Phone Number Location Using Python GitHub Repository - Tech2 etc
[![Track Phone Number Location Using Python GitHub Repository](https://user-images.githubusercontent.com/80243988/136017398-8416c97d-cbe2-425e-af98-6475eb99e696.PNG)](https://www.youtube.com/watch?v=Dz3rSZHnKkM)

## Here you will get the answers of - 

**How To Track Phone Number Location With Python. track phone number location using python. Track phone number location using python github. how to track a phone number github. How to track location using python. python code for live location. Phone numbers Python.**

**Phone numbers python documentation. python phone number validation. get current location google maps python. How do I create a location tracker in Python?. How do I get coordinates in Python?. How do I track my phone using python?.**

## ABout this project
We have created this project just for fun. Tracking someones location is more that what you think. In this project we are just trying to determine the country name based on the coutry codes. Nothing else.
**Some words from OpenCage:**
OpenCage can NOT be used to determine the location of a mobile phone simply based on the number of the phone.

I’m forced to clarify this because we are getting more and more support requests from people who have been mislead by YouTube tutorials that a simple python script can be used to determine the location of any phone simply by entering the phone number.

Here is what is actually happening:

- The phone number is entered and a library is used to turn the country calling code into the name of the country. For example numbers starting with +91 becomes India, +880 is Bangladesh, +34 is Spain, etc.
- The country name is then sent to our geocoding API as a forward geocoding request (placename to coordinates). We then return the coordinates of the center of the country. For example we turn India into 22.3511148, 78.6677428, roughly in the middle of Uttar Pradesh.
- People get confused and angry as to why the coordinates are not actually where the phone is physically located.

Unfortunately there is no such thing as magic, and neither we, nor anyone else, have the ability to derive a phone’s location from an input string like India or Spain.

Source: https://blog.opencagedata.com/post/we-can-not-convert-a-phone-number-into-a-location-sorry

## Properties Used

YouTube: https://youtu.be/Dz3rSZHnKkM

Phonenumbers Python Library: https://pypi.org/project/phonenumbers/

OpenCage Geocoding Module for Python: https://pypi.org/project/opencage/

OpenCage Geocoding API: https://opencagedata.com/

Folium: https://pypi.org/project/folium/

PyCharm (Code Editor): https://www.jetbrains.com/pycharm/
