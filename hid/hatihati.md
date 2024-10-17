# Sketch Upload Interference
As a consequence of the multi-processor design of the UNO R4 WiFi board, uploads may fail with a "No device found on ..." error when the board is running a sketch that uses the HID capabilities.

For this reason, you should use the following procedure to upload under these conditions:

1. Press and release the button marked "RESET" on the board quickly twice. The LED marked "L" on the board should now be pulsing.

2. Select the port of the board from the menu in Arduino IDE. The port might have changed after the previous step, so make sure to verify that it is selected.

3. Upload your sketch as usual.
