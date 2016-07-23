Installation Instructions for Infinity Theme for Conky

Step 1 : Install Conky
                Ubuntu :   apt-get install conky-all
                Fedora : yum install conky
                see documentation for other distros in order to install conky
Step 2.1 : Extract the Infinity tar file
Step 2.2 : Set background of your desktop to background provided. (background.jpg)
Step 2.3 : Install monofur-font from folder monofur-font 
Step 3 :  change the name of conkyrc to .conkyrc
                change name of lua to .lua
                change name of conky to .conky
Step 4 : Copy these 4 files .conkyrc, .lua and .conky and todo files to your home directory
                cp * ~/
Step 5 : Open .conkyrc and adjust the screen resolution according to your desktop
Step 6 : Also adjust haunted.lua in .lua directory according to screen resolution
Step 7 : I have  also given u a file named rev-eng.psd in order to modify the background image of conky so u can adjust it too and edit the profile pic.
Step 8 : Some scripts for mem,cpu etc have been written separately . you can delete them and use them as you wish.
Step 9 : Now you are ready to run conky
                open terminal and type $chmod a+x ~/.conky/startconky.sh
                                                            $sh ~/.conky/startconky.sh
                                                            it will start after delay of 15
                                                            add this file to startup application in order to load it at startup
            OR
            Run Directly :   $ conky&
You may get unknow variable warning. Don't know what it is and is bugging me even.

Step 10. In case you are facing problem with black background, of Conky, don't worry open Compiz Config settings manager and navigate to Effects > Window Decoration and in Shadow input append '& !(class=Conky)' without quotes.

Step 11. Open .conkyrc and edit names and settings depending on your creativity

