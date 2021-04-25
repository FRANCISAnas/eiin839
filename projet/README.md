# Let's go biking !

## by Anas Francis
## 25 april 2021
## © All rights reserved

This project is composed of 4 sub-projects:

	1. MyProxy which is going to store in its cache for a certain amount of time the requests to the api JCDecaux.
	2. RoutingWithBikes which is going to get all JCDecaux's stations and then use that list to compute the path from starting address to destination address.
	3. HeavyClient which is going to do the sale thing as the light-client except there wont be a map, but it will print the instructions in the console.
	4. light-client which is going to be used by users the input their start and en itinerary and display the result inside a leaflet map.

The project contins also hosted service so that you don't need to make any furthur configurations. Just go to HostedServiceProxy\bin\Debug and execute HostedServiceProxy.exe in adminstrative mode. (Same for HostedServiceRoutingWithBikes).

Once your both terminals are executed just open index.html file inside the light-client folder and then input your start and destination addresses and hit the "get path" button.

You should wait a little bit (like 15 seconde, yes it's very long Lol ^^) and enjoy the displayed map in leaflet ;)

To test the REST API of Routing with bikes service, with postman, please excute the following link (assuming you've already stared the hosted services, as exolained previously) : 
http://localhost:8733/Design_Time_Addresses/RoutingWithBikes/RESTBikeRoutingService/computeRoute?addressOfStart=4%20rue%20du%20sauveur%2069007%20lyon&addressOfDest=28%20Rue%20des%20Heros%20marseille

To make a new research, you must refresh the page

see the project on github : https://github.com/FRANCISAnas/eiin839/tree/benjaminvella-main/projet

An example of input : 

Address of start : 4 rue du sauveur 69007 lyon
Address of destiniation : 28 Rue des Heros marseille


