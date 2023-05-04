irBnB clone - Web dynamic
For this project, students are expected to look at this concept:
AirBnB clone

Resources
Read or watch:
Selector
Get and set content
Manipulate CSS classes
Manipulate DOM elements
Document ready
Introduction to AJAX
GET & POST request
HTTP access control (CORS)
import this repository
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
How cool it is to request your own API
How to modify an HTML element style
How to get and update an HTML element content
How to modify the DOM
How to make a GET request with jQuery Ajax
How to make a POST request with jQuery Ajax
How to listen/bind to DOM events
How to listen/bind to user events
More Info
Import jQuery
<HEAD>
    <SCRIPT src="https://code.jquery.com/jquery-3.2.1.min.js"></SCRIPT>
</HEAD>
Install Flasgger
$ sudo apt-get install -y python3-lxml
$ sudo pip3 install flask_cors # if it was not installed yet
$ sudo pip3 install flasgger
jsonschema exception
$ sudo pip3 uninstall -y jsonschema 
$ sudo pip3 install jsonschema==3.0.1
No module named 'pathlib2'
$ sudo pip3 install pathlib2
Expose ports from your Vagrant
In your Vagrantfile, add this line for each port forwarded

# I expose the port 5001 of my vm to the port 5001 on my computer
config.vm.network :forwarded_port, guest: 5001, host: 5001
Tasks
Task	Intro
0. Last clone!	For this project you will fork ...
1. Cash only	Write a script that starts a Flask web application ...
2. Select some Amenities to be comfortable!	For the moment the filters section is static, let’s make it dynamic! ...
3. API status	Before requesting the HBNB API, it’s better to know the status of this one ...
4. Fetch places	Replace the route .., Create a new template.., Write a Javascript script ...
5. Filter places by Amenity	Replace the route .., Create a new template .., Write a Javascript script ...
6. States and Cities	Now, reproduce the same steps with the State and City filter ...
7. Reviews	Let’s add a new feature: show and hide reviews! ...
Completed
 0.
 1.
 2.
 3.
 4.
 5.
 6.
 7.
Authors
Abinet Tesfu - Github Melat Samuel - Github

Fourth part of Airbnb: 0x06. AirBnB clone - Web dynamic
