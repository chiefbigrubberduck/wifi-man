# Wifi-Man (Wi-Fi Manager)
![Static Badge](https://img.shields.io/badge/Language_-_Bash-green)
![Static Badge](https://img.shields.io/badge/Wi--Fi_-_Management-blue)
![Static Badge](https://img.shields.io/badge/OS_-_Linux-neon)
![Static Badge](https://img.shields.io/badge/Version_-_0.5-red)
![Static Badge](https://img.shields.io/badge/Project%20Status%20-%20Beta-green)
![Static Badge](https://img.shields.io/badge/OS%20-%20Linux-cyan)

---------------------------------------------------------------------------------------------------------
> [!WARNING]
> As shown above, this project is still in beta, and does not guarantee stable performance, it has been tested, and performed fine, but reliability can not be guaranteed for every system. Your system won't explode ;), but the code is not yet been completely controlled, revised, and edited for max stability throughout the script.
----------------------------------------------------------------------------------------------------------

## What is this?
 wifi-man is a tool for controlling advanced aspects of Wi-Fi in Linux - and only in Linux -. It allows you to...
 * Make interfaces
 * Remove interface (Not working, still under development)
 * Set your card into monitor mode
 * Set your card into managed mode
 * Change TX Power
 * Change regulatory domians
 * Change hostname
 * Change interface name
 * Change interface MAC address
 * Turn promiscuous mode on/off
 * Print phy information
 * Print interface information
 * Look up MAC address's (Not working, still under development)

Check out the wiki's [about](https://github.com/chiefbigrubberduck/wifi-man/wiki/About) for more info.

## Get Started
To get started, check out the wiki page [here](https://github.com/chiefbigrubberduck/wifi-man/wiki/) for downloading, setting up, and using wifi-man to it's fullest. It is first **highly** recommended to check out the requirements and any other below paragraphs

## Requirements
### Software Requirements:
> [!IMPORTANT]
> All programs should be in your system $PATH to ensure everything works smoothly.
* iw                                                                                                                          
* ip                                                                                                                          
* hostname                                                                                                                    
* bash (newer version (5.0 +), preferably)                                                                                    
* systemctl (currently, will change in the future)
* aircrack-ng
* macchanger
* iwconfig (Pretty-print only.)
* rfkill                                                                                                                      
                                                                                                            
### Things to know
* Basic understanding of Wi-Fi in Linux
* Basic CLI commands
* Bash execution and option use
* Basic understanding of Wi-Fi subsystem and how modes, settings, etc, all work.

If you don't know one of these things, check out the wiki for starting info [here](https://github.com/chiefbigrubberduck/wifi-man/wiki/)

-----------------------------------------------------------------------------------------------------------------------------

## Disclaimer
I (chiefbigrubberduck) am not responsible for any issues or problems (of any sort) regarding anything related or tangentially related to the hosted scripts. The user must be aware of what these scripts will do. They are for educational purposes only. Anything outside of what is considered "educational" is not endorsed by me, nor my collaborators. Regard the AGPL-3.0 License for more information.
