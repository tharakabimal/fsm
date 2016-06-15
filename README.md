# IOC v 0.9.5
Fuel station management [![IOC](https://img.shields.io/badge/IOC-prototype-green.svg)]() 

<img src="http://i.imgur.com/NLUgrak.png?1">

[Beta version demo](https://www.youtube.com/watch?v=-Up9RFzHCOU)

<b>Documentation</b>

Based on model,view,controller strategy (MVC). Entire code is well organized into different parts 

Models - located in Models folder 
Views - located in View folder 
Controllers - located in Controllers folder

<b>Routing configuration</b> - with the apache configuration via .htaccess .php is hidden from the URL 

Example - http://localhost/IOC/login 

Consider login in the above URL as part 1. A controller with the same name ‘login’ exists in the controller folder 

http://localhost/IOC/login/checkin

Consider checkin in the above URL as part 2. A method exists with the name ‘checkin’ in the corresponding controller , here it’s login , which handles the logic

<b>Database configuration</b> - PDO is used for database interaction and the Connection file is located in libs/Database.php
