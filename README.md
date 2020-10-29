This is sprint 1 of the project HotZone.

Feature:

1. List the location data in the database.
2. Input the location name and search for the location using HK GeoData API.
3. Select a location data and insert the data into the database.
4. If you do not select any choice and submit the form, the app will ask you to submit again.

Limitation:

1. Tha app will not verify whether the location data is known to HotZone or not.
2. Once you have selected and submitted, the action cannot be canceled.

The above limitations shall be overcome in sprint 2.

Remark:
In order to send an HTTP request from Django, I install the 'requests' module using 'pip install requests'.
If you encounter the issue of 'ImportError: No module named requests', please use this command to install the module.
