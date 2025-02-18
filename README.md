SlimeGloves: VR Haptic Gloves Fork



Warning: These are ideas based on LucasVRTech’s work, and I’m not working on them yet due to lack of materials. No code has been written, and no software has been tested with SteamVR or OpenGloves.

This project is a fork of LucidGloves, combining SlimeVR trackers with the LucidGloves framework. The goal is to integrate SlimeVR tracker data into the glove's functionality, specifically for finger tracking, without needing additional controllers. I aim to use SlimeVR trackers for the full-body data and rely on that for the glove's finger tracking data. However, this idea is in its conceptual phase and has not been implemented yet.

The SlimeGloves will include Arduino/ESP32-based VR haptic gloves, lightweight without controller attachments, and compatible with SteamVR through OpenGloves. I also plan to integrate buttons like X, Y, A, B, joysticks, and possibly an Oculus button for additional control options. This is designed to work in a standalone manner, allowing phone connection via IP to the headset and sideloading an app version that communicates with the VR headset.

This idea is inspired by my personal needs as a VRChat user, and I want to create an immersive, controller-free experience. Although I'm working on the SlimeVR app for standalone functionality, the actual hardware and software have not been tested yet. The integration is still a work in progress.

If anyone wants to collaborate or help with this project, feel free to comment on my fork. I welcome any assistance in making this a reality.

LucidGloves - Firmware and 3D Printer Files

This repo contains the Arduino firmware and STL files for Prototypes 3 through 4 of the LucidGloves. These gloves allow you to use your hands in VR. Please follow along with LucasVRTech’s developments on his TikTok page:
LucasVRTech TikTok

Building your own gloves

Start here at the wiki:LucidGloves Wiki

Support

Join the LucidVR Discord server for assistance:LucidVR Discord

Firmware

Open the firmware files located in the firmware/lucidgloves-firmware folder. By default, the firmware is configured for an Arduino Nano using serial. To configure the firmware, change the defines in the lucidgloves-firmware.ino file.

Configuration instructions are here:Configuration InstructionsFirmware Troubleshooting Guide is here:Firmware Troubleshooting Guide

Tested boards:

Arduino Nano

ESP-WROOM-32

Supported Communication Methods:

USB Serial

Bluetooth Serial (on ESP32 boards)

BLE (Soon, not yet available)

Hardware

STL files for 3D printing are located in the hardware folder.

Required parts for each hand:

Spool (5x)

Tensioner (5x)

Cover (5x)

Holder (5x)

GuideRing (Will need resizing) OR GuideNode (3.1) (2+ per finger, 1+ for thumb)

EndCap (1x per finger, will need resizing to fit)

Guide for printing parts:

Printing guide

Required parts:Parts ListOptional:

Joysticks for locomotion (DIY treadmill in the works)

Buttons (Many can be replaced with gestures; one button is required for autocalibration)

More information will be available soon on the LucidVR site.

SteamVR Compatibility (OpenGloves)

This project uses the OpenGloves OpenVR driver for compatibility with SteamVR, which is downloadable from Steam:OpenGloves on Steam

Source code available on GitHub:OpenGloves GitHub

Other LanguagesEnglish | 简体中文

Disclaimer:

This is a personal project, and I'm not working on it actively due to lack of materials and resources. Feel free to reach out if you'd like to contribute to the project!
