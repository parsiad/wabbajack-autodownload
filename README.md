# This project has been archived! Please use the actively maintained 👉 [Nexus AutoDL](https://parsiad.ca/nexus-autodl) 👈 instead.

<p align="center">
  <img alt="Wabbajack Autodownload" src="https://raw.githubusercontent.com/parsiad/wabbajack-autodownload/master/static/logo.png">
</p>

## About

**Wabbajack Autodownload** automates downloading a [Wabbajack](https://www.wabbajack.org) modlist *without* a premium Nexus account.

## Motivation

Without a premium Nexus account, you have to manually click on a download button every time a new mod is added to the queue. Since modlists often have hundreds of mods, this is time consuming. Wabbajack Autodownload is a macro automates clicking on the download button for you.

## Warning

Using a bot to download from Nexus is in direct violation of [their TOS](https://help.nexusmods.com/article/18-terms-of-service):

>  Attempting to download files or otherwise record data offered  through our services (including but not limited to the Nexus Mods  website and the Nexus Mods API) in a fashion that drastically exceeds  the expected average, through the use of software automation or  otherwise, is prohibited without expressed permission. **Users found in  violation of this policy will have their account suspended.**

Use this at your own risk.

## Known issues

Some users have reported that the macro fails to automatically click the Nexus ![slow download](https://github.com/parsiad/wabbajack-autodownload/blob/main/images/slow_download.png?raw=true) button. If you encounter the same problem, refer to [this thread detailing a workaround](https://github.com/parsiad/wabbajack-autodownload/issues/1#issuecomment-988203548).

## Usage

1. Download [Wabbajack Autodownload v0.1.1](https://github.com/parsiad/wabbajack-autodownload/archive/refs/tags/v0.1.1.zip)
2. Download the [portable release of Pulover's Macro Creator (PMC) v5.4.1](https://github.com/Pulover/PuloversMacroCreator/releases/download/v5.4.1/PuloversMacroCreator-Portable.zip)
3. Extract the contents of `wabbajack-autodownload-0.1.1.zip`
4. Extract the contents of `PuloversMacroCreator-Portable.zip`
5. Launch PMC by opening `MacroCreatorPortable\x64\MacroCreator\MacroCreator.exe`
6. In PMC, select *File > Open* from the menu
8. In the Open dialog, choose `wabbajack-autodownload-0.1.0\wabbajack_autodownload.pmc`
8. Start downloading a mod list with Wabbajack until you get to a "Click the download button to continue screen"
   ![](https://raw.githubusercontent.com/parsiad/wabbajack-autodownload/main/static/step8.jpeg)
9. **Important: Minimize all windows except for PMC and Wabbajack and make sure that Wabbajack is maximized**
10. In PMC, select *Macro* > *Play Current Macro* (PMC should automatically minimize afterwards)
    ![](https://raw.githubusercontent.com/parsiad/wabbajack-autodownload/main/static/step10.jpeg)
11. When Wabajack has finished downloading the mod list, you can exit PMC
