
# PMD2 Data Monitoring Project   python version

## Introduction  
This project is a desktop application built with [Tkinter](https://docs.python.org/3/library/tkinter.html) that monitors sensor data from a PMD2 device. The system supports real-time monitoring, configurable CSV export, and long-term data recording. Users can select CSV export fields, configure the recording frequency and duration, and monitor the recording progress via a progress bar. The recorded data is then exported as a CSV file.

## Features

- **Real-Time Data Monitoring**  
  Displays sensor readings in three sections: ATX24, EPS, and PCIE & HPWR. Each section shows Voltage, Current, and Power values.

- **CSV Export**  
  Exports the current data in a horizontal format as a CSV file. The export fields are configurable and the file name includes a timestamp.

- **CSV Settings**  
  Provides a dialog for users to choose which CSV fields to export. The settings are saved in a JSON file and automatically loaded on startup.

- **Long-Term Data Recording**  
  Users can configure:
  - **Recording Frequency**: Set the interval from 0.1 seconds up to 5 minutes.
  - **Total Recording Duration**: Set the overall recording time from 1 minute to 1 hour.
  For example, if you choose to record once every second for 5 minutes, the exported CSV file will contain 300 data points. The CSV fields are configurable as above.

- **Calibration**  
  - **Reset**: Resets all calibration parameters to their default values (gain = 1.0, offset = 0.0).
  - **Write**: Updates the global calibration parameters based on user input. 
  - **Load**: Loads calibration parameters from a JSON file and updates the dialog fields.
  - **Store**: Saves the current calibration parameters to a JSON file for future use.

- **Fixed Window Size**  
  The main window and all dialogs are fixed in size to prevent resizing by the user.





---
[切換到中文](README_py_zh.md)
