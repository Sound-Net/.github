# SoundNet

SoundNet is a passive acoustic monitoring device based on [SoundTrap](https://www.oceaninstruments.co.nz/) 4 channel devices. SoundNet devices contain small clusters of four hydrophones which enables them to calculate the bearing to a received vocalisation. They then have an attached sensor package containing a depth and advanced [mti-3](https://www.xsens.com/sensor-modules/xsens-mti-3-ahrs) orientation sensor. This allows the devices to determine a _geo_referenced_ 3D bearing to vocalisations. Devices can be deployed on fishing nets or the seabed free floating and still determine accurate geo-referenced bearings. When two or more devices detect the same sound they can triangulate it's position allowing the tracks of animals to be determined. 

### 🔧 Core Utility Programs

SoundNet devices rely on three key desktop utility programs to configure, maintain, and process data from sensor packages:

- **[xsensViewer](https://github.com/Sound-Net/xsensViewer)** — A viewer and testing tool for SoundNet sensor packages, used to inspect and validate sensor package output during development, calibration, and field deployment.
- **[sensorfirmwareupdater](https://github.com/Sound-Net/sensorfirmwareupdater)** — Updates the firmware running on SoundNet sensor packages, ensuring devices in the field can be kept up to date with the latest features and fixes.
- **[sudunarchiver](https://github.com/Sound-Net/sudunarchiver)** — A simple GUI application for extracting sensor data from compressed `.sud` files, allowing users to unpack and access recorded sensor data without needing to first extract raw `.wav` audio files.

### 📦 Related Repositories

- [soundnet_firmware](https://github.com/Sound-Net/soundnet_firmware) — SoundTrap firmware for SoundNet devices.
- [sensor_firmware](https://github.com/Sound-Net/sensor_firmware) — Firmware for SoundNet sensor devices.
- [sensor_firmware_binary](https://github.com/Sound-Net/sensor_firmware_binary) — Builds for sensor firmware.
- [soundnet_array](https://github.com/Sound-Net/soundnet_array) — Modelling the movement of hydrophone arrays.
- [soundnet_mat](https://github.com/Sound-Net/soundnet_mat) — MATLAB functions for SoundNet.
- [soundnetR](https://github.com/Sound-Net/soundnetR) — R workflow for data analysis.

### 📚 Publications

- [First detailed insights into harbour porpoise...](https://royalsocietypublishing.org/rsos/article/13/8/rsos260565/483031/First-detailed-insights-into-harbour-porpoise) — *Royal Society Open Science*
- [Publication in Methods in Ecology and Evolution](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.13828) — *British Ecological Society journal*
