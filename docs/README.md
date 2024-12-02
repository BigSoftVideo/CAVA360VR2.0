This is a help guide for setting up and using our open-source beta version of multi-user CAVA360VR<sup>2</sup> (_Collaborate, Annotate, Visualise, Analyse 360 video in VR_). CAVA<sup>2</sup> is multiuser Virtual Reality application. 

## Requirements

Anyone who wishes to take part in a CAVA360VR session needs to install a version of the software on their laptop/PC with Windows 10 /11.
An internet connection is required.
    - A VR headset installed with SteamVR.
    - Most high-end VR headsets work that have to be connected to a computer, eg. HTC VIVE PRO, HP REVERB, OCULUS RIFT, HTC COSMOS, VALVE INDEX have been tested.
    - The Oculus Quest 2 (with link) has been tested.
- Make sure that your audio speakers and microphone are working on your computer or your VR headset.
It is best to always use headphones to avoid feedback looping.

## How to download and setup CAVA360VR<sup>2</sup>

It is quite easy to download a release as a ZIP file, unzip it on your computer and run it on WINDOWS 10/11.
The downloaded file is the CAVA<sup>2</sup>Builder, which you need to create a CAVA<sup>2</sup> session. 

Follow these steps
## Step 1: Prepare your system
- Ensure you have a **VR-ready computer** with internet connectivity.
- Supported HMDs include:
  - Oculus Rift S
  - HTC Cosmos
  - HTC VIVE Pro 1+2
  - HP Reverb G2
- Confirm that built-in microphones are functioning for voice communication.

## Step 2: Obtain the CAVA360VR2 Installer
- Acquire the **CAVA360VR<sup>2</sup>** and the **CAVAbuilder tool** via this link.

## Step 3: Install and Configure CAVA360VR2
1. Launch the **CAVAbuilder tool**.
2. Input and verify your **Photon Voice App ID**:
   - Sign up for Photon Engine services [here](https://www.photonengine.com/).
   - Note: The free version supports up to 20 users.
3. Add synchronized (it is really important that the media files are in sync) media files to your project:
   - 360-degree videos
   - 2D video files
   - Images or 3D objects

## Step 4: Build Your Project
- Use **CAVAbuilder** to compile all files and settings into a project folder.
- The folder will include:
  - Selected files
  - A unique **Photon App ID**
  - An executable file (`.exe`) for launching the CAVA360VR<sup>2</sup> projet

## Step 5: Launch and Connect
1. Share the project folder securely with all participants.
2. Open the `.exe` file on each participant's system.
3. Enter your preferred username when prompted.
4. Begin your collaborative VR session:
   - Use the **file browser**, timelines, and interaction tools to navigate and collaborate in the VR space.

---

### Notes
- Ensure all media files are synchronized before importing them into the project.
- Follow GDPR regulations by avoiding the inclusion of sensitive personal data.


```
CAVA360VR_Data
MonoBleedingEdge
CAVA360VR.exe
UnityCrashHandler64.exe
UnityPlayer.dll
```

## How to use CAVA360VR

Every time you run CAVA360VR you will need to connect to a remote server to access the CAVA room that you or another user has designated.
Everyone has to connect to the same room, so type the exact name into the box.
Also, add your username for the session.
Don't forget to untick the VR mode box if you do NOT have a VR headset.
If the room name is correct, then you will see other users and their avatars in the room if they are already present.

NOTE: The basic version of CAVA360VR comes with the Lego Demo Project, which has two videos and a transcript included under a Creative Commons CC BY-NC-SA 4.0 International license.
The video data for this project is about 160MB.
When you run the software and enter the designated room, then you will see the 360 video automatically.
The 2D video clip and the transcript are only visible if the user performs the command to do so (see below).

## Commands and shortcuts for VR

This diagram lists all the commands and shortcuts that are possible for both modes.

![Diagram of commands](media/commands.png)

The top section shows the VR controller button actions.
Sometimes you have to play around with the controller for the VR setup to find where the `MENU 2` button or the grip is located.
On some VR controllers the touchpad is replaced by a joystick; experiment to find out how to view and select from the options on the radial menus.
The bottom section shows the keyboard commands and shortcuts to do the equivalent action in non-VR mode.
Non-VR mode users can do everything that VR mode users can do, except use the drawing tools to mark up the video.

## Cooperating in CAVA360VR rooms

It is really important to appreciate how CAVA360VR affords a particular democratic model of virtual cooperation.
Basically, all tools are shared by everyone, even though you can reposition them independently.
If a tool is opened, then everyone sees it, eg. timeline, transcript, 2D video window or mirror cam.
Note that where the tool is located in 3D is personal to each avatar.
Anyone in a room can open and close the shared tools, and the action will happen for everyone, eg. if someone closes the open timeline, then it is closed for everyone.
Thus, it supports more democratic participation than the host/guest model.
For example, Zoom has a built-in host/guest model that means the host(s) have more privileges than guests.
Guests cannot do very much in a room, unless given permission by the host(s).
However, the CAVA model can be abused if everyone tries to take control of a tool at the same time!
Thus, cooperation can often be better managed via the share audio chat channel.
Note that the mirror cam supports a host, but anyone can take over the host role at will.

## Setting up CAVA360VR with your own data

To setup CAVA360VR to use your data, then there are some steps to follow:

1. Locate and open the folder in which the CAVA360VR program resides and run the program.
2. 


Next steps:
1. Test by opening CAVA360VR to see if the 360 video (and 2D video or transcript) are present and playable.
2. 

NOTE: If you require encryption, then you will have to use free zip archiving software such as _7-zip_ or _WinZip_.
You can add a password and send that password to everyone who needs to unzip the archive.
This zip archive can be sent to everyone who needs it.

NOTE: If a user downloads the wrong CAVA360VR package, then they will see a different 360 video and things will get a little crazy.

## NOTES on 360 and 2D video clips
- The resolution and bit rate of the 360 video should be as high as possible, otherwise the video playback will be blocky and blurred in VR.
Use the raw footage and render at a high bit rate using the camera software (or _MistikaVR_).
- The dimensions of the 360 video should be 4K or UHD, eg. from 3840x1920 up to 4096x2160.
Do not use 5K or 8K clips.
Many computers will not be able to play such high resolution video, especially not when playing at the same time as an inserted 2D video clip.
- Stitch the raw footage carefully so that the stitch lines between lenses are not too visible.
- With mobile 360 cameras use stabilisation while filming or stabilise later in the camera software.
_MistikaVR_ has tools for re-stabilising, but it is not free and it takes some effort.
- The 2D video clip is best at HD resolution, not 4K.

## Notes
- At present, CAVA360VR is a prototype. 
It is not meant for public use.
Please do not share with others unless permission has been given by the developers.
- CAVA360VR uses a multi-user network gaming service that requires an account.
When setting up a session with your own data, you will need to apply for an account on the Photon platform.
This will allow 20 simultaneous users per session of CAVA360VR.
If several groups are using the same accoount at the same time but independently, then the total number of users still cannot exceed 20.
- Because of these restrictions, please do not use CAVA360VR for non-research purposes.

## Bug reports

How to enter a [bug report issue](https://github.com/BigSoftVideo/CAVA360VR-beta-testing/issues/new/choose).
This link will only work if you have an account on GitHub and are a member of the beta-testing group.

## Feature requests

How to enter a [feature request or enhancement](https://github.com/BigSoftVideo/CAVA360VR-beta-testing/issues/new/choose) to a tool issue.
This link will only work if you have an account on GitHub and are a member of the beta-testing group.

## Tracking bugs and feature requests

You will be able to track bugs and features as issues in our [project KANBAN board](https://github.com/BigSoftVideo/CAVA360VR-beta-testing/projects/1).
This link will only work if you have an account on GitHub and are a member of the beta-testing group.

## Using DISCORD to communicate directly with the developers

We are using a channel `#beta-cava360vr` on our BigVideo server on Discord to share thoughts and fix issues interactively with beta-testers.
Please ask the developers if you would like to join.
