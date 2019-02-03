# RPiEasy update
Update script for RPiEasy (Linux)

:warning:THIS IS A BETA TEST VERSION!:warning:

* RPiEasy is a Easy MultiSensor device based on Raspberry PI project from
  enesbcs (Alexander Nagy) https://github.com/enesbcs/rpieasy

## Getting started: ##
* copy `rpieasy-update.sh` in the same directory where the RPiEasy directory are (not in the RPiEasy directory !!)

* `sudo chmod 777 rpieasy-update.sh`
* `sudo ./rpieasy-update.sh`


## What does the script ##
* makes a 'rpieasy-update' directory
* copy the 'data, files, img' from you RPiEasy directory (copy your settings)
* clone https://github.com/enesbcs/rpieasy.git in to the 'rpieasy-update' directory
* Exit RPiEasy
* removed the 'RPiEasy' directory
* copy the 'rpieasy, data, files, img' directory together as last update 'RPiEasy'
* removed the 'rpieasy-update' directory
* started RPiEasy

If it went well then you have the latest RPiEasy with your own settings.

If your 'Console log Level' active then you can read the output in the 'nohup.out' file in the 'RPiEasy' directory. 

If you want to keep the 'rpieasy-update' directory with your settings to the next update than
uncomment line 21 and comment line 49 in the 'rpieasy-update.sh' script.


## useful links: ##
*  https://github.com/enesbcs/rpieasy
