# Dataset


## Sensors
- UWB: LinkTrack P-B 9ea(anchor 8ea, tag 1ea) 60 Hz   
- IMU: UM7 20 Hz


## Ground truth

- Motion caputre system Qualisys ARQUS A5 cameras


---
In our experimental setup, we utilized a drone equipped
with both a tag and an inertial measurement unit (IMU).     
The tag was integral to the Ultra-Wideband (UWB) system, which
operated at a frequency of 60 Hz using the LinkTrack P-B device.     
This system included one tag and eight anchors arranged
in a rectangular cuboid formation, spanning coordinates from
(0, 0, 0) to (8.86, 8.00, 2.20) meters.     
The IMU, specifically the UM7 model, was set to a default frequency of 20 Hz and was mounted directly below
the tag to ensure accurate data collection.     
Additionally, the setup featured a motion capture (MoCap) system comprising
ten Qualisys ARQUS A5 cameras, capable of operating at
700–1400 frames per second (fps) with resolutions of 1–5
megapixels (MP).
The MoCap system provided 3D tracking
with ±0.06 mm resolution and a camera latency of 1.4 ms,
with data recorded at 10 Hz for reference ground truth.
