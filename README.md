# solar_car_hardware
Repository for solar car electrical hardware made in Altium Designer. This project is set up to provide all documentation, design and data validation required for the Badgerloop Solar Car PCBs. This repository builds off of our previous work in the SpaceX Hyperloop Competition.

## Prerequisites
Altium only works on Windows. See  [Altium System Requirements](https://www.altium.com/documentation/18.0/display/ADES/Altium+Designer+-+((System+Requirements))") for more information. An internet connection is required to connect to the license server and dual monitors are nice to have. Microsoft Excel is required for BOM generation.

## Installation
1. Make an [Altium live account](https://live.altium.com/signin?prmGotoUrl=https://www.altium.com/altium-designer/) so you may work on Badgerloop's 10 person floating license
2. Contact Lucas Maddox or Shelby Riggleman to be added to the [Badgerloop Team Account](https://dashboard.live.altium.com/) and the Badgerloop [Github](https://github.com/badgerloop-software"). You may continue to step to step 8 without requiring an active license. If there is a delay for some reason, you can work on Altium training and practice on CAE computers or through [Citrix](https://remote.engr.wisc.edu/vpn/index.html), but we are usually able to add new users within 24 hours. Badgerloop currently supports Altium 21.2.0. 
3. Download the latest version of [Altium Designer](https://www.altium.com/products/downloads) 
4. Install Altium. Default file paths will work.
5. Install [Git Bash](https://gitforwindows.org/") Git Bash (or whatever BASH emulation tool you are comfortable with)
6. Open Git Bash
7. Type the following commands into the command prompt window:
   + cd ../..
   + mkdir git
   + cd git
   + git clone https://github.com/badgerloop-software/hardware.git
   + cd hardware
   + git checkout -b <your-username_training>
   + Open Altium and sign in. You are now on a training branch that you will complete your first getting started project on if you are new to Altium. 
8. Go to User (Silhouette in the top right corner) -> License Management. Then Click Sign In and enter your username and password associated with Altium Live and accept the warning. It's also a good idea to check Sign me in when I start Altium Designer if you'd like to save a little time.

_NOTE: If you go click "Sign In" directly from User, you will be asked for a server address. This is not what you want. Go back to step 7 and hit License Management instead of Sign In._ 

8. Click Use to claim a license. If you are not using a valid license, you will be able to view files in Altium Designer but you will not be able to make edits. Ensure that you are choosing an Altium Designer License and not our PDN License. That's something else. 
9. You are now ready to use Altium. See [Training](#training) for more details on how to get started. 

## Github Basics
+ [Here](https://wiki.badgerloop.org/index.php/Github_How_To) is a breakdown of what git/github is and how Badgerloop utilizes it. If you'd like more information or a different description, [here](https://www.freecodecamp.org/news/learn-the-basics-of-git-in-under-10-minutes-da548267cc91/) is a pretty good page that breaks down the basics.

## Training 
+ Multivibrator Project: The Multivibrator Project from Altium is hands down the best training resource for getting started with Altium. We suggest that everyone new to PCB design complete this tutorial on their own prior to working on Badgerloop schematics or boards. While we want to help everyone as much as possible, it's on you to get a bit of a background. Feel free to ask Ezra, Shelby or Ryan if you have any issues with the tutorial. [Multivibrator Tutorial] (https://www.altium.com/documentation/18.0/display/ADES/From+Idea+to+Manufacture+-+Driving+a+PCB+Design+through+Altium+Designer). This guide goes "From Idea to Manufacture" and drives a design all the way though rough-drawing your circuit, making library symbols and footprints, schematic capture, placement, layout, and routing, as well as manufacturing outputs. 
+ Additionally, keep an eye out for any Badgerloop sponsored training sessions! 

## Acknowledgements
+ [Altium](www.altium.com), for being an amazing sponsor! 
+ Dave Jones of the EEVBlog, as we'd have no idea what we were doing without his videos.

