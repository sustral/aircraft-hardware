# Prototype Aircraft Hardware

![](/img/PedestalView_1.jpeg)
![](/img/FrontView_1.jpeg)
![](/img/SideView_1.jpeg)

## Electronics

   - Main Computer: Nvidia Jetson Xavier
   - Flight Computer: PixHawk 4 (Previously Navio2)
   - Optical Flow Sensor: PX4Flow
   - Lidar Sensor: LIDAR-Lite v3
   - Camera: Logitech C920
   - Backup Receiver: OrangeRx R615X
   - Propulsion: 4x 960KV
   - ESC: 4x 20A
   - PDU: Custom
   - Cabling: Custom (except for some PX4 data cables)
   - Batteries: 2x 4s 1500 mAh

## 3D Models

All frame components aside from the legs were custom designed and 3D printed.

![](/img/Full_1.png)
![](/img/Full_2.png)

![](/img/BatteryClasp_1.png)
![](/img/BatteryClasp_2.png)

[Battery Clasp](/battery-mount)

![](/img/BatteryRails_1.png)
![](/img/BatteryRails_2.png)

[Battery Rails](/battery-mount)

![](/img/BatteryCase_1.png)
![](/img/BatteryCase_2.png)

[Battery Case](/battery-case)

![](/img/PowerDistributionUnit_1.png)

[Power Distribution Unit](/power-distribution-unit)

![](/img/BottomPlate_1.png)
![](/img/BottomPlate_2.png)

[Bottom Plate](/bottom-plate)

![](/img/GPS&RXMount_1.png)

[GPS and Receiver Mount](/gps-and-receiver-mount)

![](/img/Camera&OpticalFlow&LidarMount_1.png)

[Sensor Mounts](/sensor-mounts)

![](/img/TopPlate_1.png)

[Top Plate](/top-plate)

   - The legs are from a DJI F450 clone kit

## Safety Rig

The weather where I live often does not lend itself to outdoor testing. To enable year round
testing, I built a rig that ensures safe indoor test flights.

![](/img/SafetyRig_1.jpeg)

The rig is made of an autoretracting upper tether that prevents the aircraft from hitting the floor, a lower 
tether that prevents the aircraft from hitting the upper beam or the roof, and a set of takeoff legs. The takeoff
legs fall away as soon as the aircraft's mass no longer holds them in place. Landing flat on the ground is not 
possible with this setup so test flights generally end with the aircraft hanging on the upper tether.
