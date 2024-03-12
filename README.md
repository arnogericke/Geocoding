# Geocoding

# Goal
The goal of this project was to use ChatGPT to help develop a program, in Python, to facilitate Reverse Geocoding for a Client Project.
I have no previous experience in Python, and leveraged GPT and Prompt Engineering to complete the development of my program.

# Technology Used
I used ChatGPT to develop my Geocoding/Reverse-Geocoding application.
At first I used GeoPY as my API to facilitate the request. The hard limits of 1300 calls per day, and 1 call per second, worked as a test bed to prove that I had a working version of the app, and to test ourput was correct.
After some initial trial and error, finally correct output was achieved. The hard api call limit was the next issue that had to be resolved, as the database was quite large.
I searched for another geolocation API service and came across OpenCage.
OpeCage had blocks of API calls for sale, and per second calls were limited to 15 calls per second on the cheaper blocks.
I purchased the necessary API call block, to complete the project, and modified my app code to use the OpenCage API key I received.
Results were as expected, and this part of the project was completed sooner than expected.

# Project Description

Reverse Geocoding for Client, using supplied Lat/Long information to return useable locations for assets in their portfolio.
Initial scope: Client has numerous in field assets, but inaccurate location information, making management and proper exploitation of those assets inefficient, and in some cases impossible.

# Job Scope:     
               My service offering was to create a reverse geocoding program to draw information from a supplied database containing all their assets' latitude and longitude information.
               I used ChatGPT to help create the aformentioned program using Python. Having no experience in Python, I wanted to leverage AI Prompt Engineering to create a solution to the initial scope.
               Development costs were for My Company, Inceptio (Pty) Ltd., as the program ownership remains with The Company.
               Once the program was running properly, and output was correctly generated and exported to a new database, we had a product.

# Deliverable:    
               Initial scope was completed in record time.
               Customer files were created using the data we supplied, based on their supplied database.
               Customer was able to vastly improve their service offering, as well as cull any assets which were underperforming.
               Proper asset management for the client was top of the list of priorities.

# Benefit:     
               I was able to learn a lot regarding what is possible leveraging AI and Prompt Engineering, helping me create a program which is tiny in scope, but performs very well.
               Having no experience in coding or using AI, I gained experience in solving a known problem, using unknown to me techonlogies.
               Using free services at first like Geopy as a test bed, then quickly realising the limitations of that service, I was able to keep development costs low.
               Continued development allowed me to move on to faster paid API's, which cut output time down 94%, from one return a second to 15 returns a second.
               Cost benefit was maximised.
