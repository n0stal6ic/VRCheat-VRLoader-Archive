# VRCheat-VRLoader-Archive
VRCheat &amp; VRLoader Archive (By: zombiebossx)


VRCheat for VRChat 2018.2.3p1 Build 621

Your account must be able to upload avatars in order for avatar stealing to work.

Instructions:
Download VRLoader from @zombiebossx (link below)
Go to your VRLoader folder and copy VRCheat.dll into the Modules folder.

VRLoader installation (copied from @zombiebossx 's thread.
Installation

Locate your VRChat managed folder (Typically at "..\Steam\steamapps\common\VRChat\VRChat_Data\Managed")
Move the VRLoader folder into the "Managed" folder

**At the top left of the screen you can see what your display name is so you can keep track of it when copying people's names**
**Players who are using a stolen avatar will have a blue nameplate color**

While a player is selected (press escape and click on their avatar), you can press these keys:

Scroll wheel button: Save their avatar (Console will ask avatar's name)
T: Teleport to that player
M: Send that player a notification message

For the following keys you don't need to have a player selected:

CTRL + G: Teleport to a specific player (Console will show you a playerlist and ask you to type in a substring of the player's name)
CTRL + M: Teleport every pickup item to you (Might cause a crash when changing worlds)
CTRL + O: Toggle bone ESP (Enabled by default)
CTRL + L: Toggle name ESP (Disabled by default)
CTRL + F: Toggle fly mode (Use Q and E for going up/down)
CTRL + Sroll wheel button: Save avatar by ID
CTRL + K: Save current avatar
CTRL + DELETE: Delete current avatar from saved avatar list



-----------------------------------------------------------------------


(New Cheat for VRChat) VRLoader and VRCheat
My old post for VrCheat is outdated and i just found a new updated VrCheat from the creator himself (Harekuin), so i gathered up everything you will need. (VRLoader and the Module for VRCheat.)
All this is just a copy from Harekuin's post.
-------------------------------------------------------------------------------------------
VRLoader
VRLoader allows developers to easily create and share cheat modules for VRChat, and also makes it easy for you to use these modules.

Installation

Locate your VRChat managed folder (Typically at "..\Steam\steamapps\common\VRChat\VRChat_Data\Managed")
Move the VRLoader folder into the "Managed" folder

Installing Modules

To install a module you must copy the module .dll into VRLoader's Modules folder
Run VRLoader.exe after you've started VRChat.
-------------------------------------------------------------------------------------------
Creating Modules

To create a module, you have to create a class library project in Visual Studio.
VRLoader will find load your .dll and look for any module classes.

Requirements

Your project must target .NET Framework 3.5
Your module classes must be decorated with the Module Info attribute and inherit from VRModule
Your project must reference VRLoader.dll and UnityEngine.dll
(You'll most likely also need to reference other game .DLLs)
-------------------------------------------------------------------------------------------
Things you can do in this updated cheat:
1. Fly
2. Bone ESP
3. Name ESP
4. etc (Check instructions text file in VRCheat Folder)
-------------------------------------------------------------------------------------------

Sorry guys, I'm a little late to this. Update dropped 2/10/19
Example of VRLoader with Modules:
