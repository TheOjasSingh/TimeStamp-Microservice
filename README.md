
# [Timestamp Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice)
The API endpoint is GET [url]/api/timestamp/:date_string? If the date string is empty the service uses the current timestamp. If the date string is valid the api returns a JSON e.g. {"unix": 1479663089000 ,"utc": "Sun, 20 Nov 2016 17:31:29 GMT"}. API accepts unix time. If the date string is invalid the api returns a JSON having the structure {"error" : "Invalid Date" }.

Example usage:
https://savory-desert-salesman.glitch.me/api/timestamp/2015-12-25
https://savory-desert-salesman.glitch.me/api/timestamp/1451001600000

Example output:
{"unix":1451001600000, "utc":"Fri, 25 Dec 2015 00:00:00 GMT"}
