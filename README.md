# Gruvy_Holiday_XML v1.0.0

This app is for making the Holidays.xml file for the Gruvy Rainmeter Skin's Calendar
It uses an API https://date.nager.at/Api to get the data of the Public Holidays.

You can find the config.cfg in the root folder of the app.

IMPORTANT!!!
1.  Before you run the app, make sure you edit the config.cfg file.
	This file contains:
		a. Which country's holidays you want in the XML file(country code)
		b. The folder where the current Holidays.xml is stored. (WARNING!!! The app is going to overwrite the old Holidays.xml, just so you know.)
2.	Make sure you are connected to the internet. Without internet access, the app cannot make a request to the API.

Additional information:
	The app will always use the current year, when requesting data from the API.
	
If these prerequisites are done you just need to run Gruvy_Holiday_XML.exe
and the Holidays.xml will be created in the folder specified at the config.cfg file.

Enjoy :)
