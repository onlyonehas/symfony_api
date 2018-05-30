# symfony_api
Using any of modern frameworks ( Laravel, Lumen, Symfony etc) to create an API for "accommodation booking" platform that must have a User Interface that must do the following:


Have a CRUD functionality for a property
name, address, description, image
Add availability for a property.
start_date, end_date
User must be able to find accommodations available between dates chosen. Response must include number of days that each property is available, for dates provided.
Ex: Between 15 April - 25 April some properties will be available for 2 days, as availability of those is 10-17th April.
User must be able to book an accommodation for number of days provided. You must handle errors when users are cheeky 😃 

Optional:
Create basic User Interface with CSS framework of your choice that consumes your API
Create User Authentication
Find properties by distance (3 miles) provided from a location (latitude: xxx, longitude: xxx)

Add any tables and models you think are required.


IMPORTANT:
It is expected that your code will work out of the box. You must write Installation documentation.
You can use Vagrant box + provision files to spin your project on virtual machine that will be accessible from an IP.

Important to keep in mind “Can the other person read and test what I have created?”
