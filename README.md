# Pico-TC08-PT104-Labview-Arduino-Heater-Controller
This 32-bit Labview program is a PID based heater controller that reads the set point (SP) temperature via Picolog TC-08 and/or PT-104, and controls the heater output through PWM. 

Things you need to do before running the Labview Program.
  1. Install MakerHub's Lynx package in Labview
  2. Download Picotech's Picolog SDK
  3. Upload Lynx firmware onto Arduino

Important items to take note:
  1. You have to use 32-bit Labview to run this program as it uses a 32-bit Picolog device driver.
  2. Arduino Communication Port must be selected prior to running the program. All other parameters will be dynamically changed, or can be      updated by clicking the “Update Settings” button, during run-time.
  3. Only the first channels for RTD and TC are used as feedback channel. Please ensure that the sensors intended to be used for feedback      control are plugged into the first channels.
