# CMD Commands to Obtain Information on PC Components

This document provides a list of CMD commands to get detailed information about various hardware components of a PC, such as the motherboard, RAM, processor, etc.

## General System Information

To get general system information:

```cmd
systeminfo
```

## Motherboard Information

To get information about the motherboard:

```cmd
wmic baseboard get product,manufacturer,version,serialnumber
```

## BIOS Information

To get information about the BIOS:

```cmd
wmic bios get name,serialnumber,version
```

## Processor Information

To get information about the processor:

```cmd
wmic cpu get name,numberofcores,numberoflogicalprocessors,maxclockspeed
```

## RAM Information

To get information about the RAM:

```cmd
wmic memorychip get manufacturer,capacity,speed,serialnumber
```

## Hard Drive Information

To get information about the hard drive:

```cmd
wmic diskdrive get model,serialnumber,size
```

## Graphics Card Information

To get information about the graphics card:

```cmd
wmic path win32_videocontroller get name,adapterram,videoprocessor
```

## Network Information

To get information about network adapters:

```cmd
wmic nic get name,MACAddress,Manufacturer
```

## Connected Devices Information

To get information about connected devices (USB, etc.):

```cmd
wmic path win32_pnpentity get name,manufacturer,deviceid
```

## Batch Script Example

Here is an example of a batch script that runs all these commands and saves the results to a text file:

```batch
@echo off
echo General System Information > system_info.txt
systeminfo >> system_info.txt

echo. >> system_info.txt
echo Motherboard Information >> system_info.txt
wmic baseboard get product,manufacturer,version,serialnumber >> system_info.txt

echo. >> system_info.txt
echo BIOS Information >> system_info.txt
wmic bios get name,serialnumber,version >> system_info.txt

echo. >> system_info.txt
echo Processor Information >> system_info.txt
wmic cpu get name,numberofcores,numberoflogicalprocessors,maxclockspeed >> system_info.txt

echo. >> system_info.txt
echo RAM Information >> system_info.txt
wmic memorychip get manufacturer,capacity,speed,serialnumber >> system_info.txt

echo. >> system_info.txt
echo Hard Drive Information >> system_info.txt
wmic diskdrive get model,serialnumber,size >> system_info.txt

echo. >> system_info.txt
echo Graphics Card Information >> system_info.txt
wmic path win32_videocontroller get name,adapterram,videoprocessor >> system_info.txt

echo. >> system_info.txt
echo Network Information >> system_info.txt
wmic nic get name,MACAddress,Manufacturer >> system_info.txt

echo. >> system_info.txt
echo Connected Devices Information >> system_info.txt
wmic path win32_pnpentity get name,manufacturer,deviceid >> system_info.txt

echo.
echo System information has been saved to system_info.txt
pause
```

By running this batch script, all system information will be saved to a text file named system_info.txt.