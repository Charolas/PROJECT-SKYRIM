# PROJECT Skyrim

![PROJECT Skyrim banner image](https://user-images.githubusercontent.com/27007797/198385604-5258bfdf-76ec-449d-b196-ad4fffab9410.png)

---

<h3 align="center">
<a href="https://discord.gg/hBMst84gUp"><img alt="Discord"src="https://www.freepnglogos.com/uploads/discord-logo-png/discord-logo-logodownload-download-logotipos-1.png" width="50" height="50"></a> ︱
<a href="https://www.nexusmods.com/skyrimspecialedition/mods/76466"><img alt="Nexus" src="https://raw.githubusercontent.com/github/explore/781dbc058383a2ee8259ebbab057292f16172d5e/topics/nexus-mods/nexus-mods.png" width="50" height="50"></a> ︱
<a href="https://www.patreon.com/charolas?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=creatorshare_creator"><img alt="Patreon" src="https://decentered.co.uk/wp-content/uploads/2019/12/patreon-logo-png-badge-7.png" width="50" height="50"></a> ︱
<a href="https://ko-fi.com/charolas"><img alt="ko-fi" src="https://github.com/user-attachments/assets/d28aa735-9a96-499e-a5de-a4de0c13e555" width="50" height="50"></a>
</h3>
<hr>
   
# 1 Introduction

**PROJECT Skyrim** is a content-rich, <ins>gameplay-focused</ins> modlist that aims to enhance the Skyrim experience through expansions, overhauls, and thoughtful adjustments to existing systems and features.

Additionally, **PROJECT Skyrim** includes <ins>optional, unintrusive adult content</ins>. No NSFW content will appear in your game unless you actively choose to engage with it.

> However, this means you must be of legal age in your country of residence to play **PROJECT Skyrim**; it is your responsibility to be aware of your country's age requirements.

**PROJECT Skyrim** is designed to be played in __3rd person POV__.

# 2 System Requirements
## 2.1 Recommended Hardware Specs
* VRAM
  * 8 GB 
* RAM
  * 32 GB

### 2.2.1 **Performance Presets**
There are three versions of the Skyrim `.ini` configuration files available on Nexus; *low*, *medium*, and *high*. There is only a small difference between them in terms of visuals (texture resolution remains the same), but choosing a more performance-friendly preset may yield more FPS.

> The **PROJECT Skyrim** `.ini` files are located at `%ProjectSkyrimLocation%\profiles\Default`. 

## 2.3 Disk Space Requirements
* Disk Space as of PS version [0.9.1.x]:
   *  10 GB for the WJ PS file from Nexus
   * 265 GB for the mod downloads
   * 435 GB for the installation folder
   *  40 GB for the page file
*  ...**so a total of 750 GB**
   * During the installation process, as archives get unpacked and files moved around, there will be some *temporary* overhead space needed.

> **PROJECT Skyrim** must be installed on an <ins>**internal SSD**</ins>, it <ins>**cannot**</ins> be installed on an HDD or an external drive of any kind.

Your <ins>**downloads**</ins> can be on a different drive than the installation, even an HDD. Network and OneDrive locations will not work, however.

After the installation has finished, the downloads can technically be deleted, but it is recommended to keep them on an external drive, instead, if you are short on space. You will need them again when updating to a new version. Repairing the installation (by re-running the installation via WJ) will require only the downloads of the mods that are broken, usually.

# 3 Pre-Installation Preparations
## 3.1 Pagefile Configuration
### PROJEKT Skyrim version [0.9.0.x]
* Press `Windows + R` to open the "*run*" prompt.
* Type `sysdm.cpl ,3` and press `Enter`.
* In the "*Performance*" section, press "*Settings*".
* Select the "*Advanced*" tab at the top .
* In the "*Virtual memory*" section, press "*Change...*".
* Disable "*Automatically manage paging file size for all drives*".
* Select the drive that PROJECT Skyrim is installed on, and select "*Custom size:*".
* Set a mininum **and** maximum size of `40960 MB`.
* Click "*Set*" and "*OK*".
* Press "*Yes*" when prompted to reboot your computer.
> This is <ins>NOT OPTIONAL</ins>, you cannot skip this step no matter how big your RAM is.

### PROJEKT Skyrim version [0.9.1.x]
* As of version [0.9.1.x], the page file will be configured for you automatically towards the end of the installation process.

## 3.2 Install SSE Creation Kit (Steam)
Install the **[SSE Creation Kit](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/)** (free) into the same library/folder that your Steam Skyrim SE installation is located in. You do not need to run it before installing the modlist.

### PROJEKT Skyrim version [0.9.0.x]
For PS version [0.9.0.x], the Creation Kit must be <ins>downgraded</ins> as follows:

* Press `Windows key + R` to open the "*run*" prompt.
* Paste `steam://open/console` and press `Enter` to open the Steam console.
* There, paste `download_depot 1946180 1946183 2725999750516785042`  and press `Enter`.
* Then, paste `download_depot 1946180 1946182 926444740758492387` and press `Enter`.

The console will tell you where it has placed the depot folders; open them and place all files <ins>from within</ins> into `%SteamLibraryLocation%\steamapps\common\Skyrim Special Edition\`, overwriting when prompted. If <ins>not</ins> prompted, you did it wrong...

### PROJEKT Skyrim version [0.9.1.x]
For PS version [0.9.1.x], you do not need to downgrade the Creation Kit anymore. If you downgraded the CK previously:

* Verify/update the SSE Creation Kit via Steam to restore it to the latest version.

## 3.3 Microsoft Visual C++ Redistributable Package
Mod Organiser 2 (MO) and Wabbajack (WJ) require Visual Studio to be installed.

Download and install the x64 version of "*Visual Studio 2015, 2017 and 2019*" from **[here](https://aka.ms/vs/16/release/vc_redist.x64.exe)**.

## 3.4 Microsoft .NET Framework
Wabbajack (WJ) requires .NET versions 5 and 8, <ins>specifically</ins>.

Get them **[here](https://dotnet.microsoft.com/download/dotnet/5.0/runtime)** [<ins>both</ins> the **desktop app x64** and **console app x64**] and **[here](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.4-windows-x64-installer)** and install them if you do not have them already.

## 3.5 Other
* **Windows**
  * Your operating system must be up-to-date.
* **Antivirus/Firewall**
  * Third-party AVs will interfere during the installation and often even during play. Creating exceptions is usually not sufficient, and not recommended for security reasons. Windows Defender is fine and all you need nowadays; uninstall anything else.
* **Overlays**
  * Game overlays have been under suspicion to cause instability, so it is generally recommended to turn them off. That includes the Steam overlay.
* **[Skyrim Special Edition (Steam)](https://store.steampowered.com/app/489830/The_Elder_Scrolls_V_Skyrim_Special_Edition/)**
  * Wabbajack does not support pirated copies of the game, and neither do we.
* **[Nexus Account](https://www.nexusmods.com/)**
  * Premium recommended for automated downloads and higher download speed.
* **~~[VectorPlexus Account](https://vectorplexis.com/)~~** 
  * VectorPlexus is permanently down, please join the Discord to acquire any missing mods from the backup links.
* **[Mega Account](https://mega.io/)**
  * Required for some files not hosted on Nexus.
* **[LoversLab Account](https://www.loverslab.com/)**
  * You no longer need to log into LoversLab in Wabbajack *before* the installation, you will be prompted *during*.

## 3.6 Steam Library Location
Your Steam library <ins>must not be located</ins> in `Program Files`, this is a special folder protected by Windows UAC, which will cause issues down the line. Follow [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to move your library somewhere else.

> No support will be provided to people with Skyrim located in `Program Files`.

## 3.7 Vanilla Skyrim Setup
Start with a fresh installation of **[Skyrim Special Edition or Anniversary Edition](https://www.nexusmods.com/skyrimspecialedition)**. You should also clean out the "*Skyrim Special Edition*" folder in `Documents/My Games/` by deleting its contents.

Launch Skyrim via Steam once: Start the game and exit once in the main menu. This will ensure any settings files required by Wabbajack are created in the Skyrim directories.

Set the Game language to English - This is <ins>mandatory</ins> for installation. Open the Steam Skyrim "*Properties*" window, navigate to the "*Language*" tab and select "*English*" from the dropdown menu.

After the modlist installation has finished, nothing you do to your Steam Skyrim installation will interfere with **PROJECT Skyrim**, it is its own, self-contained instance. This also means you can have several WJ modlists installed at the same time (but you cannot __merge__ them). 

# 4 Installing the Modlist via Wabbajack
Make sure you have performed all the steps above <ins>before</ins> continuing with the installation!

## 4.1 Create Folders
Create three new folders at (or close to) the root of your drive:
* `Project Skyrim`
* `Wabbajack`
* `Wabbajack Downloads`

> <ins>Do not</ins> put your downloads folder **inside** the installation folder, even if WJ suggests this automatically!

![unknown (1)](https://user-images.githubusercontent.com/116535023/197645646-cdc7d058-43c0-403f-80cb-038ea317f0cb.png)

## 4.2 Download Wabbajack

Get the `.zip` file of the latest release of Wabbajack **[here from the homepage](https://www.wabbajack.org/)** or from the **[GitHub page](https://github.com/wabbajack-tools/wabbajack/releases)**, put it into your "*Wabbajack*" folder and extract it.

* It should include:
  * `Wabbajack.exe`
  * `wabbajack-cli.bat`

## 4.3 Download the PS WJ file & INIs
Download the **PROJECT Skyrim Wabbajack files** and the **ini files** **[here](https://www.nexusmods.com/skyrimspecialedition/mods/76466/?tab=description)** and put them into your "*Wabbajack*" folder.

Then extract the `PROJECT Skyrim x.x.x.x.zip` file.
* It will contain:
  * `PROJECT SKYRIM.wabbajack`
  * `PROJECT SKYRIM.wabbajack.meta.json`

## 4.4 Run Wabbajack
Open `Wabbajack.exe` in your "*Wabbajack*" folder. 

Click the cog/settings button at the bottom left, and log into your Nexus and Mega accounts.
![Nexus and Mega Login image](https://github.com/user-attachments/assets/49ad1c96-77aa-4e03-96a7-93fad2630b96)

Select "*Browse Lists*" on the left side:
![Browse List image](https://github.com/user-attachments/assets/eca0b2eb-3f85-4414-ae8b-356411138dd4)

Select "*Install From Disk*" at the top right...
![Install From Disk image](https://github.com/user-attachments/assets/e0fa014f-23ae-45c3-ae70-0aebf2b4572b)

.... then point it to your "*Wabbajack*" folder and select the `Project Skyrim x.x.x.x.wabbajack` file:
![Wabbajack File image](https://github.com/user-attachments/assets/2dc646ef-b71b-4293-b0bb-614d5ef21dba)

Set your paths as follows:
![Paths image](https://github.com/user-attachments/assets/808b3fd6-27f1-4f99-b5ad-811732f46b63)

Then press the "*Install*" button in the bottom right.

> Some mods may have to be downloaded manually. A window will pop up with the site to download the mod from. **Pay attention**: At the top of the window, it will tell you which file exactly to download. If you have downloaded the wrong file it will let you know at the end.

## 4.5 Installation Complete
If the installation finished successfully - great! Press "*Create Shortcut*" to create a shortcut to the custom instance of Mod Organizer that you will be using to launch **PROJECT Skyrim**, and then close Wabbajack.
![Shortcut image](https://github.com/user-attachments/assets/d15c0a8e-07c6-492f-a344-f4616e84af01)

> You must use the instance of Mod Organiser that comes with PROJECT Skyrim, easily recognizable by the dark mode UI.

### 4.5.1 Installation Failed?
There may be some missing mods, giving you an error; Wabbajack will let you know which mods have issues in the log at the bottom left, and in the browser window that opens in the end.

![Faillure image](https://github.com/user-attachments/assets/fe5685e0-9250-42f7-a8f7-2673789ae6c4)

> The WJ log can also be found at `%locationOfYourWabbajackFolder%\Wabbajack\%version#%\logs\Wabbajack.current.log`.

Our community has compiled a list of mods that often give users trouble. Join the Discord and find them in the *backup links channel*. Download any that you have an issue with and put them in the "*Wabbajack downloads*" directory (<ins>do not unpack them</ins>), then resume the installation process by repeating the steps under "*4.4 Run Wabbajack*".

> If you need to restart Wabbajack for any reason, you won't need to re-acquire any mods you have already downloaded, WJ will continue where it left off.

### 4.5.2 If Wabbajack is complaining about the "*Curios*"
* Go to your Steam Skyrim SSE `Data` folder, and locate:
  * `ccbgssse037-curios.bsa` and 
  * `ccbgssse037-curios.esl` 
* Note whether the file name is spelled lower-case-c "curios" or upper-case-C "Curios", then delete these two files.
  * If the file name was <ins>lower-case-c "curios"</ins>:
    * Open Steam, go to `Skyrim -> Properties -> Installed Files`.
    * Click on "*Verify integrity of game files*".
    * Once the files have been downloaded, rerun the Wabbajack installation.
  * If the file name was <ins>upper-case-C "Curios"</ins>:
    * Launch Skyrim SSE via Steam.
    * Select "*Creations*" from the main menu.
    * Search for `Rare Curios` and download them.
    * DO NOT Alt+Tab out, leave the game window active until the download is finished.
    * Exit the game, DO NOT verify game files.
    * Rerun the Wabbajack installation.

### 4.5.3 Other Installation Errors
If you are still having issues, join our **[Discord](https://discord.gg/hBMst84gUp)** server and check out the <ins>*faq-installation*</ins> and the <ins>*installation support channel*</ins>.

## 4.6 INI files
Now choose the correct `.ini` files for your setup: Extract the .zip archive with the `.ini` files you downloaded from Nexus; go to the subfolder with your screen's native resolution, and then choose a performance preset.

Copy the three files contained within to `%ProjectSkyrimLocation%\profiles\Default`, overwriting the existing files:
* `Skyrim.ini`
* `SkyrimCustom.ini`
* `SkyrimPrefs.ini`

# 5 Launching the Game
You can now launch **PROJECT Skyrim** from Mod Organizer by clicking the "*Run*" button at the top right; make sure the `SKSE` executable is selected from the dropdown menu. 

The first boot might take a while to get going, so be patient; 5+ minutes are normal.

## 5.1 Starting a New Game

> You <ins>cannot</ins> reuse any old saves from vanilla Skyrim or other modlists, and even updated versions of the same modlist are often not "save safe".

When starting a new game, you will first be stuck staring at Helgen for a while.

> Be patient, you must wait here for about 5 minutes (until the "Museum" pop-up appears) in order to allow all scripts and other content to load. This is <ins>not</ins> optional.

After closing the pop-up, to begin the game:
* Press `escape` to open the System Menu, navigate to the Mod Configurtion Menu (MCM), and select the first mod, "*Skyrim Unbound*". 
* From here you can configure your starting conditions.
  * It is recommened you do not touch the dragon timer, however anything else can be changed to your liking.

Once you are finished, click "*Begin Adventure*", you will now be moved to character creation.

# 6 Final Things
## 6.1 Safe Save Guidelines
To avoid save game corruption, follow these guidelines for **safe saving practice**:
 
* Never <ins>**quicksave**</ins> (even if you have the ability to do so, and definitely don't turn it back on if it's off).
* Never <ins>**reload**</ins> in game - quit to desktop and boot up the game fresh if you want to load a different save.
* Never <ins>**overwrite**</ins> a save, new saves only.
* Do not save during <ins>**script-heavy**</ins> moments, such as:
  * during or immediately after combat
  * moving at high speeds
  * immediately after changing cells (better *before* changing cells)
  * during dialogue, crafting, photo mode
  * during animations

## 6.2 Death Alternatives
Skyrim's script engine struggles already dealing with a vanilla game - in a modded experience, any little instability becomes magnified. Therefore:
* Do not change cells multiple times in quick succession, give scripts a chance to <ins>**catch up**</ins>.
* Keep a <ins>**death alternative**</ins> enabled to prevent reloads on death:
  * `Stay in the Fight` [v0.9.0.x]
  * `Soul Resurrection` [v0.9.1.x]

> PS version [0.9.0.6] "*Stay in the Fight*" is currently bugged and must be disabled and re-enabled via its MCM!
* Go to its MCM, find "*Pact with the Gods*" and disable it.
* Close the menu completely.
* Go back to its MCM and re-enable "*Pact with the Gods*".

## 6.3 Discord
For additional information and support, we invite you to join our **[Discord](https://discord.gg/hBMst84gUp)** server. There, you'll find FAQs addressing common questions, support channels for assistance with installation, gameplay, and modifications, as well as sticky posts with the latest important information.

If you fail to join successfully, a bot will inform you of the reason, if your DMs are open. Your account must be at least 2 days old to join, and you will need to complete a verification step. 

## 6.4 Legal
If anything happens to Charolas and he cannot continue PROJECT Skyrim, anyone is free to continue as long as they contact the team first, or the team can continue if they wish to do so. Any remaining funds that Charolas did not redeemed can be shared between the team members.
