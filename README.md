<p align="center">
  <img alt="Wabbajack Autodownload" src="https://raw.githubusercontent.com/parsiad/wabbajack-autodownload/master/static/logo.png">
</p>



**Wabbajack Autodownload** automates downloading a [Wabbajack](https://www.wabbajack.org) modlist *without* a premium Nexus account.

## Motivation

Without a premium Nexus account, Wabbajack requires you to manually click on a download button every time it adds a new mod to the download queue. Since some modlists often have hundreds of mods, this is time consuming. Wabbajack Autodownload is a macro that automates this process.

## Usage

1. Download [Wabbajack Autodownload v0.1.0](https://github.com/parsiad/wabbajack-autodownload/archive/refs/tags/v0.1.0.zip)
2. Download the [portable release of Pulover's Macro Creator (PMC) v5.4.1](https://github.com/Pulover/PuloversMacroCreator/releases/download/v5.4.1/PuloversMacroCreator-Portable.zip)
3. Extract the contents of `wabbajack-autodownload-0.1.0.zip`
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
