NOTE TO ALL FOLLOWERS: 

* [ReactOS AMD64/ARM Notes](https://reactos.org/wiki/AMD64)
* [ReactOS Build Environment (Specifically for ARM Builds) (Outdated?)](https://download.reactos.org/reactos/RosBE-Windows/arm/1.0/RosBE-ARM-1.0.exe)
* [ReactOS Build Environment (Should build all archs)](https://sourceforge.net/projects/reactos/files/RosBE-Windows/i386/2.1.6/RosBE-2.1.6.exe/download)
* [ReactOS SVN Compile Tutorial](https://reactos.org/wiki/Building_ReactOS)

### Don't want to wait for us?

You don't have to wait for an ARM build to be published here. Just install the RosBE, download the SVN. configure the source code, and run `cmd.exe /t:0A /k [drive]:\path\to\RosBE.cmd arm` which will build ROS in ARM. Then just use ninja and create livecd iso of ROS (exports as 'reactos-arm.iso'). Source: [AMD64 - ReactOS Wiki](https://reactos.org/wiki/AMD64#Building_amd64_port)

# ReactOS on ARM (Raspberry Pi)
ReactOS (ROS) on ARM research

## Update: 12-28-18 12:38:42

I was sick and missed uploading a copy of the ARM version of ROS. The first ARM iso will be released tomorrow @ 12-1PM (-06:00 Central). As stated before, this may or may not work on RPi to start out with. If you would like to submit drivers or software or even code, please make a pull request. The other updates were removed from this readme because they were starting to become unnecessary. Just look at the earlier commits to see them.

## Some Notes Regarding ROS

* ROS is an LGPL v2 licensed OS using drivers created from scratch. It may not work everywhere and it may not work on anything. Questions regarding anything else other than boot should be talked about in [ROS's forums](https://www.reactos.org/forum/)
* This version of ROS, just like WoA, is only for demo purposes and not for everyday work.
* Applications may not work on ROS (due to the incompatibility with x86 on ARM.)

## Backup Plans

If compiling ARM ISOs of ROS do not work or something then we will be instead using modified versions of Raspbian.

## Feel free to spread this. WE NEED DRIVERS FOR ROS!!
