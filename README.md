NOTE TO ALL FOLLOWERS: 

* [ReactOS AMD64/ARM Compilation Notes](https://reactos.org/wiki/AMD64)
* [ReactOS Build Environment (Specifically for ARM Builds)](https://download.reactos.org/reactos/RosBE-Windows/arm/1.0/RosBE-ARM-1.0.exe)

### Don't want to wait for us?

You don't have to wait for an ARM build to be published here. Just install the RosBE, download the SVN. configure the source code, and run `cmd.exe /t:0A /k [drive]:\path\to\RosBE.cmd arm` which will build ROS in ARM. Then just use ninja and create livecd iso of ROS (exports as 'reactos-arm.iso'). Source: [AMD64 - ReactOS Wiki](https://reactos.org/wiki/AMD64#Building_amd64_port)

# ReactOS on ARM (Raspberry Pi)
ReactOS (ROS) on ARM research

## Update: 12-18-2018 23:42:47

It has been about a month since the last update. We will start attempting an ARM build compile on Thursday. We cannot however guarantee ReactOS will work on RPi at the moment however anybody who wants to pitch in and help the project are welcome to.

## Update: 11-29-2018 22:06:52

We have obtained all necessary tools and are now preparing a PC to be used to compile ReactOS source with.

## Update: 11-16-2018 22:08:07

As of this point, we are working on obtaining tools necessary to create the ROS for RPi.  All aupport goes to the ROS team and their work on the original OS. We apologize for the long wait, we will most likely redistribute a copy of ARM by xmas. Even though it's ARM based doesn't necessarily mean it will work on the Pi. We will continue researching and keeping you guys updated.

## Things to Note About ROS

* ROS is an LGPL v2 licensed OS using drivers created from scratch. It may not work everywhere and it may not work on anything. Questions regarding anything else other than boot should be talked about in [ROS's forums](https://www.reactos.org/forum/)
* This version of ROS, just like WoA, is only for demo purposes and not for everyday work.
* Applications may not work on ROS (due to the incompatibility with x86 on ARM.)

## Backup Plans

If compiling ARM ISOs of ROS do not work or something then we will be instead using modified versions of Raspbian.

## Feel free to spread this. WE NEED DRIVERS FOR ROS!!
