# Zorin-os-vm
In case you don't know what Zorin os is it is a Linux Distribution based on Ubuntu 20.04 LTS and in this guide you will learn how to set it up on ether a virtual machine running in VMware workstation 16 or on real hardware because you want to get away from windows or MacOS. This guide is specificly for Windows 10/11 hosts but you can follow along on any other os host just note that you will have to adapt the steps to your os of choice. If you want to run this on real hardware then follow the guide here: https://bit.ly/3E8VyaZ

Download all the files provided in this project:

zorin os Core: https://zorin.com/os/download/16/core/

VMware Workstation Player: https://www.vmware.com/go/getplayer-win

Downloading and installing VMware:

Download VMware and Zorin os

Double click the exe file and go through the setup proccess

once VMware is installed go ahead and click "Create a New Virtual Machine"

there will be a menu that asks you to select an installer disk so put in the zorin os 16 iso file

For the os select Linux and then select Ubuntu 64-bit

Name the VM whatever you want and choose the folder that you want to store the VM files in a folder of your preference

select your disk size to be at least 80GB but choose the virtual disk to be stored as a single file for performance reasons

after that customize the hardware to your preference

Zorin os Installation:

after booting up the vm you will see 4 options but you only need to worry about 2 of them

if your graphics card is made by Nvidia then select the option "Try or install Zorin OS (modern NVIDIA drivers)"

if your graphics card is made by intel or amd the select the option "try or install Zorin OS"

go through the installation proccess as it guides you though it

Post installation:

when everything is installed you will be greeted with a tour telling you everything you need to know

after the tour is over we will need to install an application to improve performance and resolution

this step is going to need you to use the command line a little bit but you can just open up terminal and copy and paste the command

sudo apt update && sudo apt upgrade && sudo apt install open-vm-tools

when it asks for your password type that in and press enter when it asks you to confirm the installation

and with that done reboot and behold you now have a Linux VM to call your own now that Wasn't so bad was it.

this guide was created by Andrew E. Snow and if you want to modify this guide and release it to the public please mention Andrew E. Snow as the original author and this guide was created as a side project and im not trying to make a profit here at all and with that Thank You for making enderpirate known among the community.
