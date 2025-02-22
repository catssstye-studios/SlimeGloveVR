SlimeGloves: VR Haptic Gloves Fork

Warning:These are ideas based on LucasVRTech’s work. I am not actively working on them yet due to a lack of materials. No code has been written, and no software has been tested with SteamVR or OpenGloves. This is a conceptual project.

What is SlimeGloves?

SlimeGloves is a fork of LucidGloves, combining SlimeVR trackers with the LucidGloves framework. The goal is to integrate SlimeVR tracker data into the glove’s functionality, particularly for finger tracking without requiring additional controllers.

I aim to use SlimeVR trackers to handle the full-body tracking and rely on that data for finger tracking on the gloves. However, this is still an idea in the conceptual phase, and no functional code or tests have been implemented yet.

The Vision:

The SlimeGloves will be Arduino/ESP32-based VR haptic gloves, designed to be lightweight without controller attachments, and compatible with SteamVR through OpenGloves. The gloves will also feature buttons like X, Y, A, B, joysticks, and possibly an Oculus button for additional control options. They are intended to work in a standalone manner, connecting with the VR headset via phone IP and sideloading an app that communicates with the headset.

This is a personal project inspired by my experience as a VRChat user. I want to create a controller-free, immersive VR experience. While I am working on the SlimeVR app for standalone functionality, I have not tested the hardware or software integration yet. The project is still a work in progress.

If you want to collaborate or assist with this project, feel free to reach out or comment on my fork. I'd appreciate any help in bringing this idea to life!

LucidGloves - Firmware and 3D Printer Files

This repository contains Arduino firmware and STL files for prototypes 3 through 4 of the LucidGloves. These gloves allow you to use your hands in VR. The project is based on the work of LucasVRTech, so please follow along with their updates on TikTok: LucasVRTech TikTok

Building Your Own Gloves:

You can start here with the wiki: LucidGloves Wiki

Support:

For help with building or troubleshooting, join the LucidVR Discord server: LucidVR Discord

Hardware:

The hardware files for the gloves are located in the hardware folder. You'll need to 3D print the following parts for each hand:

Spool (5x)

Tensioner (5x)

Cover (5x)

Holder (5x)

GuideRing (Will need resizing) OR GuideNode (3.1) (2+ per finger, 1+ for thumb)

EndCap (1x per finger) (may need resizing)

Printing Guide:

Check out the printing guide for more details on how to print the parts and assemble the gloves.

Required Parts:

Parts list can be found in the Parts List.

Optional:

Joysticks for locomotion (DIY treadmill in the works)

Buttons (can be replaced with gestures, but autocalibration needs a button)

SteamVR Compatibility (OpenGloves)

This project uses the OpenGloves OpenVR driver for compatibility with SteamVR. You can download it here: OpenGloves on Steam.

The source code for OpenGloves is available on GitHub: OpenGloves GitHub.

Disclaimer:

I am 15 years old, and I want to make it clear that I’m just a teenager exploring ideas with very limited coding knowledge. I’m not yet working on this project actively due to a lack of materials and resources. The project is just a concept at the moment, and no software has been written or tested. Any collaboration or help is welcome!

While I will try to follow legal requirements, I cannot guarantee everything is perfect in terms of licensing or legal stuff. If you have any legal concerns, feel free to reach out, and I’ll do my best to address them.

Please note that I am not monetizing this project—everything is being done for fun and learning. I don’t have a job or any source of income (just do chores for family members for small tasks), so any legal action would be meaningless, as I have no financial resources. My goal is to create something cool, and I’m open to feedback, suggestions, or contributions from others who want to help.

SlimeVR Integration (Finger Tracking):

SlimeVR trackers will provide the data needed to drive the finger tracking, which will then control your VRChat avatar. This means your hand movements will be reflected in your avatar's fingers in real-time. If this integration is successful, it would be a huge step toward creating a more immersive and hands-free VR experience.

SlimeVR Licensing:

The software for SlimeVR is released under the MIT License and Apache License 2.0. These licenses allow you to freely use, modify, and distribute the software while adhering to the conditions set by the respective licenses.

MIT License: You can use, modify, and distribute the code, but you must include the original copyright notice and disclaimers.

Apache License 2.0: This includes the same freedom as the MIT License but with additional clauses related to patents, contributions, and trademarks. You can also contribute to the project under this license.

By using SlimeVR, you accept these licenses, which provide the legal foundation for the project.

How to Contribute:

If you'd like to collaborate, contribute, or help with this project, you can:

Submit issues and bug reports

Suggest features or improvements

Contribute code or hardware ideas

Help with testing (once development progresses)

Feel free to fork this repository and make your own contributions, as long as you respect the license terms.

Note: If the links or references are incorrect, please check the main project repositories or official pages for the most accurate and up-to-date information.
