# playonlinux
My PlayOnLinux script collection

## Overview
This repository contains some of the applications that I wanted to run on my (beautiful, gorgeous, amazing) Linux box. They're organized following the official Play On Linux software categories, except _tests_ folder.

Scripts state as of 8 January 2019:

| PlayOnLinux software category |         Script        |      Application     |  Status  | Notes                                                                                                              |
|:-----------------------------:|:---------------------:|:--------------------:|:--------:|--------------------------------------------------------------------------------------------------------------------|
| Development                   | enterprise_architect  | Enterprise Architect | untested |                                                                                                                    |
|                               | markdown_monster      | Markdown Monster     | fails    | - requires at least .NET 4.6.2 (it's a WPF app) and I'm not confident that it installs properly.                   |
|                               |                       |                      |          | - the app errors at startup because it cannot find some path.                                                      |
| Graphics                      | balsamiq_mockups      | Balsamiq Mockups 3   | works    | - see https://www.playonlinux.com/en/topic-16110-Script_Balsamiq_Mockups.html   
| Office                      | edraw_project      | Edraw Project   | fails    | - requires native VC++ 2015 redist                                    |
| Functions                     | POL_install_7zip      | 7-zip v18.05         | works    | - kind of useless since the lib. has native version for linux.                                                     |
|                               | POL_install_dotnet462 | .NET 4.6.2           | fails    | - .NET 3.5 installation enters infinite loop, see https://www.playonlinux.com/en/app-822-POL_Install_dotnet35.html |
|                               |                       |                      |          | - during install it complains about mscorsvw.exe                                                                   |
|                               | POL_install_dotnet471 | .NET 4.7.1           | fails    | - similar as for .NET 4.6.2                                                                                        |
|                               | POL_install_IE11      | Internet Explorer 11 | untested |                                                                                                                    |
|                               | POL_install_vcrun2015     | Visual C++ Redist. 2015 | fails | - the installer does not run; files need to be extracted and placed manually |

The scripts from _tests_ folder are just a wrapper over the content of some of the functions so they can be tested locally by importing the test script into PlayOnLinux.

## Other repositories containing PlayOnLinux scripts

* https://github.com/petchema/playonlinux
* https://github.com/corbindavenport/creative-cloud-linux
* https://github.com/lahtis/playonlinux
* https://github.com/hynner/PlayonlinuxSharedSteam

## Bibliography

* https://www.playonlinux.com/en/page-19-PlayOnLinux_script_functions_reference.html
* http://wiki.playonlinux.com/index.php/Scripting_-_Chapter_11:_List_of_Functions
* http://wiki.playonlinux.com/index.php/Components_and_Functions
* http://wiki.playonlinux.com/index.php/How_to_Contribute_a_Script

* https://github.com/Winetricks/winetricks/blob/master/src/winetricks

* https://docs.microsoft.com/en-us/dotnet/framework/get-started/system-requirements#installation-requirements
* https://www.reddit.com/r/wine_gaming/comments/8r6low/guide_how_to_install_net_45_on_64bit_prefixes/
* https://appdb.winehq.org/objectManager.php?sClass=version&iId=36818#testdata

* https://appdb.winehq.org/objectManager.php?sClass=version&iId=33811
* https://support.microsoft.com/en-us/help/2847882/prerequisite-updates-for-internet-explorer-11
* https://www.sevenforums.com/windows-updates-activation/237949-unable-install-updates-fresh-windows-7-sp1-install-2.html
* 
* https://sparxsystems.com/enterprise_architect_user_guide/14.0/product_information/enterprise_architect_linux.html
