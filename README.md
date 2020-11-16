# Sensor Log
Android Application - logs readings from various sensors at a user-specified 'Sampling Rate'.

- The Sampling Rate specified by the user in **seconds**. As the Android SDK does NOT support custom sampling rate for sensors, thus the required values were filtered out by keeping track of the time difference.

- The output file is in the `.csv` format and can be found in the `sdcard` of your device with the name `sensorlog.csv`

- The App will continue to run in the background and log the readings until it is killed either by pressing the **Back** Button or by swiping it out.

- For creating the `.csv` file, the [OpenCSV](http://sourceforge.net/projects/opencsv/) library is used.

- The `.apk` file can be found at the following path - `/app/build/outputs/apk`.

- The application supports all Android devices running Android version >= `4.0.3` i.e. `Ice Cream Sandwich` or higher.

## Sensors Covered :-
- Accelerometer
- Gyroscope
- Magnetometer


