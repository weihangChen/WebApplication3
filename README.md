# Summary
proff of concept that server1 and get dynamic js functions from server2 and hook up the functions with the html elements. When event fires,
we are able to extract information from server1 and return the data to server2. Then what server2 does using the data is another business.


# Steps to run
1. download visual studio 2019 preview
2. download this project
3. download https://github.com/weihangChen/WebApplication2
4. run WebApplication2 since it is the server
5. run WebApplication3 and click the button

# request sequence description
1. vendor asks our service for js functions through endpoint "GetScript()"
2. our service return js functions, it get hooked up with the button
3. click the button, extract info using xpath, send the product info back to our service on endpoint "GetData()"
