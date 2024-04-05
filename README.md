# Holybro X500 Drone Kit Sensor Housing

## Overview
Design files for a sensor housing compatible with the Holybro X500 Drone Kit. Houses an expandable IR temperature board, Survey3 camera, and USB wide angle camera. 

![IMG_1254](https://github.com/SHARK-Alert-System/sensor-payload-housing/assets/20687631/7ad8ca89-4d9a-459f-abe0-674c19cf3acb)


## Files
- `Survey3_Camera_Models.stl`: 3D model for Survey3 camera housing.
- `Survey3_Camera_Models.stp`: STEP file for camera model modification.
- `sensor_holder_bottom.stp`: Editable file for the holder's bottom part.
- `sensor_holder_bottomv15.stl`: Printable 3D model of the holder's bottom.
- `sensor_holder_top.stp`: Editable file for the holder's top part.
- `sensor_holder_topv4.stl`: Printable 3D model of the holder's top.

# Assembly Instructions for Holybro X500 Drone Kit Sensor Housing

## Components
1. Survey3 Camera Housing
2. Circuit Board with MLX90614ESF-BCI-000-SP-ND Temperature Sensor
3. Raspberry Pi HQ Camera or USB130w01mt
4. Velcro Straps (provided in the Holybro kit)
5. 1/4 Sized Double-Sided Prototype PCB (6 Pack, Multicolor) [Purchase Link](https://www.amazon.com/gp/product/B09ZPGJ58F/ref=ewc_pr_img_1?smid=A2E7YALNIES9BY&th=1)
6. 3M Screws with 1cm Standoffs
7. 2.5M Screws for Raspberry Pi Camera or 2M Screws for USB130w01mt Camera
8. Drone Vibration Damping Balls (Damping Bumper Rubber Ball + Anti-Drop Pins Anti-Vibration Isolator Kit for DJI Phantom 3)

## Assembly Steps
1. **Camera Installation**: Insert the Survey3 camera into the housing. Secure it with the Velcro straps from the Holybro kit.
2. **Circuit Board Setup**: Attach the temperature sensor circuit board to the provided standoffs using 3M screws. If necessary, trim the board to fit.
3. **Camera Mounting**:
   - For Raspberry Pi HQ Camera: Fix it to the circuit board with 2.5M screws on 1cm standoffs.
   - For USB130w01mt: Use 2M screws for mounting on 1cm standoffs.
4. **MLX90614 Temperature Sensor Configuration**: Set up the MLX90614 temperature sensor with the Raspberry Pi following this [guide](https://olegkutkov.me/2017/08/10/mlx90614-raspberry/).
5. **Assembling the Housing**: Connect the top and bottom parts of the sensor housing using drone vibration damping balls for shock absorption and stability.

Make sure all parts are securely assembled and verify all connections before attaching the housing to the drone.


## Usage
Modify STEP files or print STL files as needed for your sensor housing.

## Contributing
Fork, modify, and pull request to contribute.
