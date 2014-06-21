DEPRECATED in Favor of Container-Harbor a Complet Local and Remote Solution to Easy install a Dev Envirment and Choose all kind of stuff like webserver and used databases on windows and Linux that soon gets even deployed as binary.





AXAMPP <- AXWP + SXSP
======

User Voting for New Titel:
##### AXWP (Advanced eXtended Webservices Package) <- Maybe only call the Development Stack this Name
##### AXSP (Advanced eXtended Servers Package) <- maybe only call the Production Stack this Name

Project AXAMPP (Advanced Extended Apache/MySQL/PHP/Perl - GIT/MariaDB/NGINX [Webserver Complet Package]) 

The Aim of AXAMPP is to have a Single fast install able Preconfigured Server Envirment that can easy change and maybe soon Scale


Plans:
First Release Linux (debian/ubuntu) Maybe soon Linux Arch all!
Base XAMPP
Adding NGINX as Secund Choice for a Webserver
Adding Configuration PreSettings Chooser (Development, Produktion Hosting, Userdefined)

Strukture!

###### XAMPP/ <- stays Untouched 
gets Copyed or Symlinked into AXAMPP (Updater Will handle that) 
In This Repository you will find alwas a Updated version of Original XAMPP as it gets automated synced from sourceforge over our High Performant Sourceforge2GitHub Service called sf2git
But in Long Termn View we will drop XAMPP in Favor of our own structure that will raise userbility a lot.


###### AXAMPP/ 
Here Goes AXAMPP Code
In This folder will be all content of XAMPP and even the content of AXAMPP's files

##### AXAMPP/NGINX/   
Only a Placeholder but shows where nginx will be
##### AXAMPP/conf/ 
all AXAMPP Related conf goes here and has subfolders for the PreSettings overwrites XAMPP Conf files in the dirs replaces em by copys or symlinks on start

#### AXAMPP/logs/ 
all Logs.

#### AXAMPP/ds_logrotator 
Component that allows to use Direkt SPEED LogFile Handler Services to Examin your Logs and Save Storage
AXAMPP/axampp_control.sh (exe) Will get the Main Control Panel for AXAMPP but a Webmanager is Included Too!


#### EXTRAS!
more info and first Release follow soon Stay Tuned thx for Attention sorry for bad English Greetings !


