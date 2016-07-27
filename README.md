# SensorLog
An Android Application which "Logs" the readings from various Sensors at a particular "Sampling Rate" specified by the user.

- The Sampling Rate is specified by the user in seconds. As the Android SDK does not support custom sampling rate for sensors, thus the required values were filtered out by keeping track of the time difference.

- The output file is in the ".csv" format and can be found in the "sdcard" of your device with the name "sensorlog.csv"

- The App will continue to run in the background and log the readings until it is killed either by pressing the "Back" Button or by swiping it out.

- For creating the ".csv" file, the "OpenCSV" library was used. It can be found here :-
http://sourceforge.net/projects/opencsv/

## Sensors Covered :-
- Accelerometer
- Gyroscope
- Magnetometer


