# PROJECT SKYRIM
![image](https://user-images.githubusercontent.com/27007797/198385604-5258bfdf-76ec-449d-b196-ad4fffab9410.png)

---

<h3 align="center">
   <a href="https://discord.gg/qEfeWVjDgJ/](https://discord.gg/hBMst84gUp)><img alt="Discord"src="https://www.freepnglogos.com/uploads/discord-logo-png/discord-logo-logodownload-download-logotipos-1.png" width="50" height="50"></a> ︱
<a href="https://www.nexusmods.com/skyrimspecialedition/mods/76466"><img alt="Nexus" src="https://raw.githubusercontent.com/github/explore/781dbc058383a2ee8259ebbab057292f16172d5e/topics/nexus-mods/nexus-mods.png" width="50" height="50"></a> ︱
<a href="https://www.patreon.com/charolas?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=creatorshare_creator"><img alt="Patreon" src="https://decentered.co.uk/wp-content/uploads/2019/12/patreon-logo-png-badge-7.png" width="50" height="50"></a>
</h3>
<hr>



- [PROJECT SKYRIM](#project-skyrim)
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
    - [Minimum Specs](#minimum-specs)
    - [Recommended Specs](#recommended-specs)
    - [Pagefile Configuration](#pagefile-configuration)
  - [Installation](#installation)
     - [Pre-Installation](#pre-installation)
       - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
       - [Installing Microsoft .NET 5.0](#installing-microsoft-net-50)
       - [Websites & Programs](#websites--programs)
       - [Clean Skyrim](#clean-skyrim)
       - [Start Skyrim](#start-skyrim)
       - [Steam Library](#steam-library)
       - [Set the Game Language to English](#set-the-game-language-to-english)
       - [Download & INIs](#download--inis)
     - [Wabbajack Installation](#wabbajack-installation)
  - [Starting The Game](#starting-the-game)
  - [Noteworthy Mods](#noteworthy-mods)
      - [Combat Overhauls](#combat-overhauls)
      - [Playstyle Overhauls](#playstyle-overhauls)
      - [Immersive & Survival Overhauls](immersive-survival-overhauls)
      - [Quests](#quests)
   
### [Discord](https://discord.gg/hBMst84gUp) | [Download](https://www.nexusmods.com/skyrimspecialedition/mods/76466)
# Preamble

**PROJECT SKYRIM** is a modlist that is content and gameplay oriented, ***focusing on expansions, overhauls, and healthy adjustments to the systems and features that exist in Skyrim***, while expanding to become the most diverse. It focuses on gameplay, world space add-ons, quests, etc. 

**PROJECT SKYRIM** also comes with an adult content addon, that is completely unintrusive.

**`Which means that nothing will appear on your face without you wishing for it to happen, you can completely ignore, however, you must be of legal age to play PROJECT Skyrim, that is 18 in some countries and 21 in others, is up to you to know your country age requirements.`**

**`You still need to download mods from Loverlabs for installation process`**




# System Requirements

With the performance mode options being available, exact minimum requirements is hard to nail down, you may need to change INI files with lower systems.


### **Minimum Specs**
| CPU        | GPU   |  RAM  | Performance|
| ------------- |:-------------:| :-----:| :-----:|
| Ryzen 5 3600      | Nvidia GTX 1080 | 16GB RAM DDR4 | 40 FPS |




### **Recommended Specs**
| CPU        | GPU   |  RAM  | Performance|
| ------------- |:-------------:| :-----:| :-----:|
| Ryzen 5 5600x      | RTX 3070 TI | 32GB RAM DDR4 | 60 FPS |

An SSD is *REQUIRED*.  
Project Skyrim must be installed to an SSD. You *cannot* use a HDD to play Project Skyrim.  
Your Graphics Card (GPU) *MUST* have at least 8GB of VRAM to avoid any issues.

**You also need**
- ~410GB for Install 
- ~250GB for Download (This can be on a seperate drive)
- 40GB for pagefile
- Around ~80GB of additional free space during the install (This will be freed up after installation haas completed)

**Notes**
- There is very low difference between High and Medium in terms of visuals, but you can get more FPS. 
- All inis will change and vary depending on the specific area you are on game due to SKSE Plugins that will cover it for more FPS
- You can change the resolution in the SkyrimPrefs.ini (make sure to use the ini used by the Mod Organizer that is installed during the Wabajack installation. It should be located at ProjectSkyrim\profiles\Default). If you need more frames you can always decrease the resolution, it will be scaled up to fullscreen by default.

## Pagefile Configuration
  1. Press **Windows + R** on your keyboard
  2. Type **sysdm.cpl ,3**
  3. press **Enter**
  4. Under the Performance section, press **'Settings'**
  5. Click the **Advanced** tab at the top
  6. at the Virtual memory section press **'Change...'**
  7. Disable **'Automatically manage paging file size for all drives'**
  8. Click **"Custom size:"**
  9. Set a custom size for the drive Skyrim is installed on with a mininum of at least **20480MB** (40960MB if higher)
  10. Click Set
  11. Click apply & OK
  12. Press Yes to restart
  13. Restart your computer.
<br>

### THIS IS NOT OPTIONAL, YOU CANNOT SKIP THIS STEP EVEN IF YOU HAVE 256 GB OF RAM.
### AS OF VERSION 9.1 MO2 WILL ASK TO DO THIS FOR YOU. HOWEVER ITS STILL RECOMMENED TO DO IT YOURSELF.



# Installation
This is a precise and easy-to-install tutorial about the mod list Project Skyrim. We aim to streamline the process and help you to remove any doubts about the installation.
## Pre-Installation

### **Install SSE Creation Kit (Steam)**

Please install SSE Creation Kit into your Skyrim installation (from steam), it's as simply as downloading a DLC, just search it in your steam library and download it.

### **Installing Microsoft Visual C++ Redistributable Package**

I doubt you need to do this since you likely already have this installed. The package is required for MO2, and you can download it from **[Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads)**. Download the x64 version under "Visual Studio 2015, 2017 and 2019". **[Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe)** if you can't find it.
### **Installing Microsoft .NET 5.0**

Please ensure you have .NET v5.0 installed (**EVEN IF YOU HAVE .NET 6.0 INSTALLED**). The game will not launch if you do not have it installed. Download the **desktop app x64 AND console app x64 installers** from Microsoft [here](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).


<a href="https://dotnet.microsoft.com/download/dotnet/5.0/runtime"><img alt="Microsoft" src="https://user-images.githubusercontent.com/27007797/198383090-15ce8391-fbc0-49a9-acb8-94b36ce3a811.png" width="555" height="294"></a>

### Websites & Programs
- [Vector plexus Account](https://vectorplexis.com/) No longer required as Vectorplexus website is down, please join the discord to acquire any missing mods from us
- [Nexus Account (Premium recommended)](https://www.nexusmods.com/)
- [Wabbajack](https://www.wabbajack.org/)
- [Skyrim Special Edition (Steam)](https://store.steampowered.com/app/489830/The_Elder_Scrolls_V_Skyrim_Special_Edition/)
- [Skyrim Special Edition: Creation Kit (Steam)](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/)
- [Loverslab Account](https://www.loverslab.com/) You no longer need to login Loverslab in Wabbajack before the installation, Wabbajack will ask you to when needed during installation.

### Steam Library

If you have your Steam library in Program Files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else.
I will not provide support to people with Skyrim in their Program Files folder.
Locations like Documents, Downloads, Desktop, or OneDrive are NOT fine. The best location would be `C:\SteamLibrary` if you have a single drive, or whichever Drive Letter you have on your main Games drive. Such a location is also called the "root of the drive."

### Clean Skyrim
Start with a fresh install of [Skyrim Special Edition or Anniversary Edition](https://www.nexusmods.com/skyrimspecialedition). You should also clean up the Skyrim Special Edition folder in Documents/My Games/ by deleting its contents.

### Start Skyrim
Start the game and exit once you're in the main menu. This will ensure any settings files needed by Wabbajack are created in the Skyrim directory.

### Manually Downgrade Creation Kit

Creation Kit recently had an update, until Project Skyrim is updated to account for this you must manually downgrade Creation Kit yourself

How to Downgrade:

Make sure that Creation Kit (Special Edition) is installed correctly. It *must* be instaled to the same drive that Skyrim is installed on.
Open the steam console by pressing "Windows + R" on your keyboard and type "steam://open/console" without the quotes.
Then, type in the following two commands, one at a time, allowing them both to download

download_depot 1946180 1946183 2725999750516785042
download_depot 1946180 1946182 926444740758492387

Once completed, the console window will tell you where it has placed the two folders.
Navigate to them and open each folder, moving over *all* files from both of the folders to the location of your Steam Skyrim install location (Steam\steamapps\common\Skyrim Special Edition) overwriting the files when prompted


### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.


### Download & INIs
[Download Project Skyrim and the INI files here](https://www.nexusmods.com/skyrimspecialedition/mods/76466/?tab=description)
<br>
# Wabbajack Installation

Make sure you have performed all steps listed under Pre-Installation before continuing with the installation.

1. Create three new folders in your drive: "Project Skyrim", "Wabbajack" and "Wabbajack Downloads" like so:

![unknown (1)](https://user-images.githubusercontent.com/116535023/197645646-cdc7d058-43c0-403f-80cb-038ea317f0cb.png)

2. Open the downloaded Project Skyrim.rar file. To do that you can use a program like 7zip (https://www.7-zip.org/download.html). Extract the files inside to your "Wabbajack" folder.

3. Copy the Wabbajack files (https://github.com/wabbajack-tools/wabbajack/releases) to your folder "Wabbajack", it should include Wabbajack.exe and wabbajack-cli.bat

4. Open Wabbajack.exe in your "Wabbajack" folder. 
   - a) Click the cog/settings button at the top right, and login to your accounts on Nexus Mods and Vector Plexus. Do NOT skip this mini-step.

   - b) Click "Install From Disk" and go to your "Wabbajack" folder, select the "Project Skyrim.wabbajack" file.

   Set your paths like so:

![unknown (2)](https://user-images.githubusercontent.com/116535023/197653641-485bf04f-a8e1-48b1-853f-367baa510366.png)

5. Some mods will have to be downloaded manually. It will pop up a window with the site to download the mod from. At the top, it will tell you which file exactly to download.

   If you have downloaded the wrong one it will let you know at the end. Don't panic. 

   If there is an error or it closes, you won't need to re-download mods you have already downloaded.

![unknown (3)](https://user-images.githubusercontent.com/116535023/197653934-0827c09e-a077-4d3d-b94d-a39a3a6c9004.png)
 

6. When Wabbajack is done downloading the Project Skyrim modlist, there may be some missing mods, giving you an error.
Wabbajack will let you know which mods have issues in the log at the bottom left.

   Our community has compiled a list of certain mods that give our users trouble and have them within the links below.
   Join the Discord and check https://discord.com/channels/869058032506667018/1022340915236446218 for the links

   Simply download any that you had an issue with and move them to the Wabbajack download directory and re-attempt installation.

   If you are still having issues, feel free to hit up our support channel in the discord server.

8. Once you have finished installing the modlist without errors, you can open your "Project Skyrim" folder, and create a shortcut for Mod Organizer.

9. You are now on the final steps!

   Open your folders like so, "Project Skyrim" -> "profiles" -> "Default" 
   The directory address should look like in the image below:

   Open the INI files .RAR file you downloaded, and copy the files inside it into the folder. Overwrite the existing files.

![unknown (4)](https://user-images.githubusercontent.com/116535023/197654286-85c3f5f4-63e3-4ede-adb3-080ce06e48c1.png)

9. You can now launch Project Skyrim from Mod Organizer by clicking the "Run" button at the top right. Make sure "SKSE" is selected. The first boot might take a while to get going, so be patient.

   If your downloads tab in MO2 looks like this, do not be alarmed.

   Wabbajack does not download meta files (these files give you info about what you did to the mod). MO2 generates default meta files for each mod and looks at it. But yes, everything is fine.

![unknown (5)](https://user-images.githubusercontent.com/116535023/197654365-cf1a1737-cd2a-4514-a19b-2dbdffe49bd2.png)


# Starting The Game

Follow these instructions whenever you start a new playthrough:
   
   Start a new game, you will appear over Helgen, please wait at this screen for at least 5 minutes. This is to allow all scripts and other content to load. This is *not* optional. Failure to do so will result in problems. AGAIN THIS IS VERY IMPORTANT, DON'T SKIP THE WAITING TIME
   Once you have waited 5+ minutes, to begin the game please press escape on your keyboard and navigate to the mod config menu (MCM) and click the first mod, Unbound. 
   From here you can configure your starting situation (It is recommened you do not touch the dragon timer, however anything else can be changed to your liking)
   Once you are finished, click "Begin Adventure", you will now be moved to character creation.

# Final things

To protect your saves from damage or corruption, or major gameplay issues please follow our advice on safe saving

- Never quicksave (Even if you have the ability to do so, and definitely don't turn it back on if its off)
- Never reload while already in game. Quit to desktop if you want to reload (Main Menu is not good enough, full quit to desktop)
- Never overwrite a save, new saves only
- Do not save during, or immediately after combat
- Do not save during script heavy moments
- Do not save immediately after changing cells, better to save before changing cells
- Do not change cells multiple times in quick succession, give the game chance to catch up with loading and scripts before changing again
- Do not spam saves, something like every 10 minutes (while following everything else) is good
- Keep Stay in the fight OR Soul Resurrection enabled to prevent reloads on death
- Clear out your old saves regularly, no need to have 100's of saves

DEATH ALTERNATIVES

We currently have two death alternative mods availalbe that can be accessed in the MCM (as of version 9.1)
Stay in the fight, and Soul Resurrection (Enable only one)
These will prevent you from dying (And causing a reload) by temporarly ending combat and causing some sort of penality based on the setup
ALWAYS HAVE ONE ENABLED

For those using 0.9.0.6, Stay in the Fight is currently bugged and must be disabled, and then enabled again in the MCM on new saves
Please remember to do this (9.1 users can ignore this)


**#For more information on gameplay, keybind, support and more, Please check out our Discord https://discord.com/channels/869058032506667018/1136301387693695038**

# For content and the "about" section of PROJECT Skyrim" Please refer to the Nexus page. https://www.nexusmods.com/skyrimspecialedition/mods/76466



If anything happens to Charolas and he cannot continue PROJECT Skyrim, anyone is free to continue as long as they contact the team (or the team can continue if they wish to do so), any remaining funds that Charolas did not redeemed can be shared between the team members.
