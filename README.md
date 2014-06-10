GlassLocation
=============

In-door location service for Google Glasses

Building bricks:
* Framework for sending sensor data from Android to the server, possibly with UDP.
* Server software that makes location evaluation in the cloud based on raw Android sensor data, and gives navigation help.
* Android software
* Glass UI

Sensor data:
* GPS (if available), cellular network location.
* Orientation (API level 3 combines gravity and magnetic field sensor data).
* Video stream (if possible)
* Images
